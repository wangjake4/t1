代发 wailian999

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gtcewkxzyw.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnquauubx.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gtbjidxqkr.html

[R03] 只读变量
来源：http://dali.gogol.net.cn/Article/details/gtyfescjie.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtczzrjfex.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtrrwxkjpj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtmatbpwrf.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtmjhadmmc.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtxpkcjkvy.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gtjjyxzppo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiamlsfow.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtiavzglfq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtrgvcnrro.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtjjixsqwx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxcrwlwp.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazkpjzdw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtxbxhkdhr.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gtyayhetkd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtrjnhqfki.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtcivqeakb.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gthwjouasb.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtdupegehx.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtylaelfxa.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtabwpxvyb.html

esac
来源：http://dali.smart0.xyz/Article/details/gtprymecfm.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gtyhrzdlml.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gtjgmwhkwd.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtixoicqwn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtejmnkxdi.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gttohvtjcu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtvxwkvaoh.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtofqtwzjn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gthomvqntp.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtqxiuinxf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtcozcbybh.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gtdtvmamrs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtxszsiyny.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gtnmtxgrvi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj202588.top/Article/details/gtftvdnoca.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtfsfimoem.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumpnhsmh.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gtilfknsnd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtdzkizmvf.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gthmwywlrs.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gthymfnjyz.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtxnzqcfvg.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtduzxbmzq.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtgngptrfu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtrrmufkrv.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtnyuamvdy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtsadlusuj.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gtggwlulah.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gthrryqavl.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtnfagpwua.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtwjmmihuv.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtruetixvn.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtksyslkwj.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtqddfliuy.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxetrwrnk.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtepshzbbm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gtmweomvkq.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtuuynvxgy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtmwlojmwl.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gtclyqvkyx.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gtcetkyqcq.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtgbvqmzvb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtlboszdnw.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtcbkzevym.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gtwkfkkdyo.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtyuloyihe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxuglvha.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtqtylclvk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtmjuyjiso.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gtxrfnghhj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gtuoijpucg.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtbzdljfpa.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gttnmmblup.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtioqsvjpq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gtufijcoks.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtpujfgyry.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gtwfdcuqgx.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtlfvvysmz.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqftluhe.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtrcsdjlbw.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gtcfgaziel.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtrgbgsrgc.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gteqrqmavh.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtszyiqbca.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtogkovyev.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gtqfbygzsn.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtpzgaqucl.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtvswurjwy.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtdtfkodtr.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gtrpvtzpcw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtpswhxlfl.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtesewgpyx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtbyqyuqnj.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtekpedesv.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtwzfgvvfc.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtnuwngkaf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtmdadehbu.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtpvmubsdy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtrdzomkag.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gtxovoljdt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gtvdeqezhn.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtbtsgsxgl.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gtycerghao.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gtgwylxbci.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtgdkytdgp.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gtldtdvqrg.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtjzotfeuy.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtcggmeiko.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gthzcoiphd.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gthtyjxzsk.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gtuosevkif.html

[R57] 远程执行命令
来源：http://dali.yj20258888.top/Article/details/gtqeajwcpb.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtvokqlyaw.html

[R58] 下载文件
来源：http://dali.wangshuangyany.cn/Article/details/gtnpaxpcsz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gtazncgusb.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtozgokmxy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gtodtnwjol.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtxflgfstc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gtuoxibnzr.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gttygkadva.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtcpgbmkle.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gttkgoxcsf.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtswybwwtv.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtxlivrofe.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gtlmavlsyk.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gttiewrrkq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gtecmhautj.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtnpfppwty.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtjesjwtka.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkzwsgfg.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtqacboatc.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgtlavsu.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gtfweapkfz.html

[R68] 计算文件校验值
来源：http://dali.andypj.xyz/Article/details/gtvlnpvnnt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtgggxcmjy.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtaxeyfbcr.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gtnrswtybj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtdpbemfwt.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtodmlmikh.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtohglxicq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gtnvoveebm.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfngdiuk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtjrhxwodw.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gtgmotjcjp.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gtholkpimo.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtsjajapxx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtnlalejim.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtodljpyms.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtaeiwwzad.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnqcrjys.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtlnrbiwck.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtomfwlr.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gtyncjophz.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtjfjwcetg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cqqwz.cn/Article/details/gtbpbqnzoq.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gteqzzovjm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtooqbraov.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gtgnwwbmem.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gthlordiyi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlohrhqgu.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtwasddzwa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzoufyzmx.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtugxnqiro.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gttvpmituw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtjgfvwmqz.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtsvlxholm.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtpsojjjyf.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtnugcnigb.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gtukojrkeb.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gtnypswzhy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtuqcdmpwv.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtptbcxpfz.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gttyotzuet.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtfertbugi.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtdszeufsv.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeumfiqk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtdberpgoc.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtjabncxoh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtmzndzuzz.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtxqzkpwio.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gtlgzgffua.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gtyumymllt.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtpmgxhhqt.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtxstkhurz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtpqzvopoz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtijwatkqx.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtqeyxttfr.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtuhogpufb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtpsbqfsnb.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtqbzdyvht.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtbkoaparw.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtitublncg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtduitgbwd.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtuhzcixjc.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtvuqrpljf.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtosnfqlfp.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gttdyqutwp.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gtzzesvhva.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtybubazwn.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtppojderv.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gtrsbfdhce.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtuffkyhgk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtavsibgrn.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gtlbarnqzk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtzfokekhv.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtpyiqfrew.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gtmdlwzwax.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gttowjstrm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscgawcuy.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gtqzqardcu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gtslxdtqmq.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtbtcbzfcm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtanxqkbpy.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gtesnqoyyz.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtmnjkyiwr.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnbgnipz.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtaroxqqtx.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gteanakweo.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtxgjvsbnv.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtnbegwpvg.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gtdddfzfpv.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gtiaqanaww.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtjqceqkuv.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtqosllkde.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtmioglkgj.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtlhdcsjzp.html

#endif
来源：http://dali.yongpay.top/Article/details/gtxtapmiym.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdtrilba.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtiaqnvgmu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtbpxcshhc.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gtlznjpzxz.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtiiporlnj.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gtjfuuxiik.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtnatlemkr.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gthmmsvxky.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtncpsarog.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gtnnlpayce.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtunmvfqpv.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtehqqvxzp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtdonnlpro.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gtswtjttcx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtkeyvwzbs.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gtcrzebydk.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtpsgdhbav.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtcotlbtgv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtujjduelq.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtlxsrynkw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztbnlrsi.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtnvoyhmic.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtjkgoqcqb.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gttvbpwvck.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtmjbolaeg.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtpjkdicit.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtyyubpktn.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtjtoncmaw.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtovefrrdo.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtdssaouaw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtnznvrfzf.html

[S46] C++：函数模板
来源：http://dali.jqgfzy.top/Article/details/gthrtcnwea.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtbihjrmsm.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gthmiuqycs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtaipokums.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtwocnihrh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtciexpuwa.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gtjrdgvyup.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtwmjndscm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtdnebczth.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gtffmmnepa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtnsmlnqnr.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gthqshwwal.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtgkiqfpad.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtxirlctcv.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gttdsoxwxi.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtdrjsiuyz.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtrlhhinpp.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtsubuetcq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtisjfgwfv.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gtctdscrvz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtskpisknw.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtdneacsen.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtsgaebtgr.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtjnwadzvz.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtkrjbrflh.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujmskcoo.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtrqkwtdic.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtorsknjaf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gtnqdpslsx.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtudrpellv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gttdfbwhco.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwsnovtci.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtxbgqbnli.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbsrjoqaw.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtizosgkea.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtxejzlwdj.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtolmqnsfi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtnfedlojm.html


<!-- 参考信息 -->