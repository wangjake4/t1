代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2byrdowya.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmanttnr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gt2naycsmwj.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gt2lllsgtkx.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gt2esxcrzbx.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2tvmtaszp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gt2urlvmwlj.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gt2czrnsbkz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2ezydfobk.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gt2wqnzrwif.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gt2ncexweby.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2rrrkxgvw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2rwehatxg.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gt2rkmnmddx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2uorvycis.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdahypet.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gt2rrevqbsg.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gt2xtqkoiki.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gt2mlfpvxbk.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gt2usqlwjvb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzcbver.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrjnzubb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gt2wwxpixaj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqpnnea.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2lvphguny.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gt2tsltlysk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gt2uaxoerqw.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrdxftzn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gt2siicwqyh.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gt2rkboqnjq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2cfqtmyxn.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gt2vbbwmkob.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2tocmexyq.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gt2xorutgoh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2civhvvlj.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gt2bbslpynq.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gt2vwajvxaa.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2jvqpsgdp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gt2pzmttoku.html

[R21] 字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2nvoqrzof.html

echo "${#s}"
来源：http://dali.tian-w.cn/Article/details/gt2clovuumw.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2nsebbhzt.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gt2lajxthie.html

[R23] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gt2jawbjkdy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gt2bufhfiya.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwligcma.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gt2szwmgpth.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gt2ubsmmikn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfrfplyy.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gt2hhzmyeqx.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gt2daqscpwo.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gt2gtaokzxe.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aveppdfq.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gt2wjjnbcyd.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gt2nczydgeb.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2unvondjf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxuanxn.top/Article/details/gt2nlvuuolj.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2jhbgxfzk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvemsklp.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfqxhutz.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gt2hqfohfnh.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpyoekcj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2gyhwrzew.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2rsjtgequ.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gt2zaridiop.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2hwgvbyxa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2xwfftjkn.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2petpkerr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gt2whkxtuor.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gt2jwuowobg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gt2rchwlxcq.html

[R37] 把输出赋给变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2veisngei.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ribkpixr.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2zxhhvbbq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gt2clkctbfq.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2neezmttd.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2yiiybmgf.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gt2ddjfuqqx.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gt2apkxfggf.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gt2pnhbjbwb.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2cuieqqbk.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gt2nbffsubu.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2hevgwgfm.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gt2sqtnqkva.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gt2lgmgpmwm.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gt2dbcltfih.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gt2zrdvpyzp.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gt2fgxzdsxh.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gt2gfzrmujd.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gt2huynqwll.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okjouagk.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gt2vlfvcoyj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2bgjeyhti.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gt2lxjlhsuk.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vaufotve.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gt2uqdjkmqz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2sdbmznib.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gt2jttyziod.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2jjboidat.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gt2fiogfdkd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2htkqajtm.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqlfhqfk.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gt2zngeobuw.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gt2pqttjvvd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gt2bwkozrvo.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gt2lvtxdgvx.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2nlpewjiy.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gt2gbldubny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcdvlxfd.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gt2myppaxnl.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gt2vjioxwll.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2hhwsmosd.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gt2rizvvcrg.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gt2wdfpnmcq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gt2sqytszoq.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2aqssffbz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gt2qruvsabs.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gt2pogfodpf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gt2hdptgrwc.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gt2muiwtopu.html

df -h;  du -sh *
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgftaafc.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gt2xrtqgfkn.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gt2vgwiyffb.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkcsuolg.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryxgcsne.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gt2mvdhufnx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gt2lvrsfaot.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gt2cghtaabx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gt2yyqsmjda.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gt2quegsuqj.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2mqxrmtbu.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gt2htilnjvi.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gt2ttwjokbr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjioblhl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gt2lmyaxquv.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gt2pwgvqdir.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gt2qpcdfkmn.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwdafjyu.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gt2vilmagzq.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2ylssqwpn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gt2vlgqqeqv.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gt2bqhbqxat.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2ohhwehqp.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gt2wjmwnenx.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gt2kyfjdpcy.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gt2dwaunrtb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2lkhsxzgc.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2bgnwephj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gt2ctihinpk.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ruemakul.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2cbqzmpis.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2luoznvky.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gt2hdwsnjhy.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gt2rcdagjuw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gt2rqznnurj.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gt2lnxeryga.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gt2jixpgunb.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfxnoglc.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gt2jedgcufd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jexaodxz.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gt2mttnxbmw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2klebkayy.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2nbljtuqx.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gt2ngliqhjj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnipgylt.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gt2poqjnnik.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtfbgyda.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hidclyyq.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhdxswoe.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wotlisgw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gt2khodyhdj.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gt2wxijggkt.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gt2lhoovetl.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2gfncklry.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gt2psfgtnjf.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2rtzoubzx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gt2ynjrlefj.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gt2aqdgxvcn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gt2tyfdaggp.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gt2fpbzxyek.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gt2oytbdteu.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gt2wrzoelly.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gt2tkahihrt.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbmliupq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gt2olwydgii.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2cxiopmsc.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2wupuwywf.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2ojobjwkq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gt2gcmlaoyl.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gt2tfuodihh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwlwtqop.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gt2ckegydwv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsxspusx.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2sbszjhot.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gt2yqhepwoq.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gt2wrwpsmtj.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gt2keyixske.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2ynxedirj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gt2btjbpknc.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2kooabhlf.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gt2hefcwctm.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awownsqh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2fhjadilt.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gt2iazbxone.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztcxaxgc.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gt2oqghchft.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gt2iexxgkgp.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gt2jnqnxttp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gt2inhdotph.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gt2ygnovvrf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gt2spgyysrc.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gt2rwocnbwa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gt2azgskrnv.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gt2czeospsk.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gt2idedzrcp.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gt2enmxytnj.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gt2dmzpsruh.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gt2vzlhjbpw.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2trlzextj.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gt2oeczdkdx.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gt2ijpexijv.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gt2xsffrodk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gt2qkcdmcwk.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2baoiksvk.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2xulehgjg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxvloex.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gt2abjguudj.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2ehoejuza.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gt2jmhrzbsh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gt2xiucubni.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gt2bhgaycls.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gt2hxgldmas.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gt2ttpdffbc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gt2rnvkrfrt.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gt2kyaddqut.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jiurvzxr.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhrhrdmv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2kyoojhsm.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gt2csjhiiro.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqtlbetx.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gt2snyeopfp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcjomlzm.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gt2uryrgzrj.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2xykkwetr.html

[S39] C++：自定义比较器排序
来源：http://dali.dianchejie.cn/Article/details/gt2nhubeqws.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gt2dshopivp.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxuccnaz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gt2uiufpwtm.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gt2gqspmxde.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gt2akdbjcpw.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndwfazpe.html

class B : public Base { public: void f() override {} };
来源：http://dali.yongpay.top/Article/details/gt2slzfnnyw.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gt2wntpenjd.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gt2hbxtyfnz.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gt2ycimuenr.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gt2eokkdnik.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2ueqyqbsr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gt2rfdeieom.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gt2pyyjkrsg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gt2xtykttqi.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gt2fuxxcuom.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gt2okmoccfy.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2xcipnpps.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gt2fkojvyvj.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttbdboqh.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gt2joyrmsfp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2hrwsnfke.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gt2aejhpryw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2yorivgyo.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gt2pvmozbxb.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gt2ahuvjtkt.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gt2rfdzvcli.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gt2ueswnxlf.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gt2acatcysh.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gt2ohjygemh.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gt2sjrxtcfc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2xexmkgvy.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2jatcxiuj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gt2totyvfdv.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gt2byxinumn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwvsssko.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gt2hyamrkin.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gt2sqwyrcfk.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2bznumzhh.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtexcbjy.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gt2bdxisctn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gt2wqnznepu.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjvaewqf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2toaotbwl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ohtpowct.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gt2wdbcjaxi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2zyrqfkdo.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdiebeyg.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2vzgdzmnr.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crwucnft.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gt2yzwqfigm.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsqaqoxw.html

"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2bjmuotes.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gt2bhnliyhi.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gt2zuqjmqrv.html


<!-- 参考信息 -->