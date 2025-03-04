from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32f415_adc.c'),
os.path.join(src_path, 'at32f415_can.c'),
os.path.join(src_path, 'at32f415_cmp.c'),
os.path.join(src_path, 'at32f415_crc.c'),
os.path.join(src_path, 'at32f415_crm.c'),
os.path.join(src_path, 'at32f415_debug.c'),
os.path.join(src_path, 'at32f415_dma.c'),
os.path.join(src_path, 'at32f415_ertc.c'),
os.path.join(src_path, 'at32f415_exint.c'),
os.path.join(src_path, 'at32f415_flash.c'),
os.path.join(src_path, 'at32f415_gpio.c'),
os.path.join(src_path, 'at32f415_i2c.c'),
os.path.join(src_path, 'at32f415_misc.c'),
os.path.join(src_path, 'at32f415_pwc.c'),
os.path.join(src_path, 'at32f415_sdio.c'),
os.path.join(src_path, 'at32f415_spi.c'),
os.path.join(src_path, 'at32f415_tmr.c'),
os.path.join(src_path, 'at32f415_usart.c'),
os.path.join(src_path, 'at32f415_usb.c'),
os.path.join(src_path, 'at32f415_wdt.c'),
os.path.join(src_path, 'at32f415_wwdt.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32F415_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
