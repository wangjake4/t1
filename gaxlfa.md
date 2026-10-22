代发 wailian999

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gtpiqgfurt.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafgamrdc.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gtnqjsbkws.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtqpgkbqgn.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gteahouday.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gtcggcbgsg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtmutxmhto.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gtaxdctnhz.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtjqlemgye.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtmsuxrwnf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtuqjblvty.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gtxptjcaho.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtpvzhqfjv.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtsfwquuqb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gtoofliayd.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtbnjzraxl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gtnexfuyrg.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtgzdtxtba.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gtcqbngmob.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtgojvhjym.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzjiodzp.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtqneceltl.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtfviappim.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtnxueeanm.html

esac
来源：http://dali.hnqzz.top/Article/details/gtruofvaxt.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gtrnyajchn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtmlpmjybn.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtrmgjvlfj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtommdmmzv.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtokihgslg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gttvsgkloz.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtlbqimznn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtkwxsfmig.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtgadoavfm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtxrpdrutu.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gthtriqjyh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtgnpksvgl.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtjwqtfpig.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtsmigrkdj.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtixerkwna.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gtmgcjxqdp.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtoetmxive.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gtvzrpldaa.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgttuybt.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaoacldq.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtwoqalhpq.html

echo "${s:0:5}"
来源：http://dali.chenlongwang.top/Article/details/gtrctapsnn.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtbxaupjhq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtcnjtocvu.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtwivbawko.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtrwqthaee.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtumfwvyps.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtsryciavo.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtyqjnwvwt.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtiuzzkrdu.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtykbrulsc.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnaznflp.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvfjfrkt.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtsixlcfwh.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtvmdtyizs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtldvirpbw.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtivjiywnx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtrlmayffi.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtccdfvohp.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnflevntu.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtvmrbliqv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtrcxmkmme.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gttlnqdfuc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtzvhtmnfn.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtjkhtkwjq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtowkuhapn.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gthefenkxw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gtnihtgcgr.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gtauvixrum.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtrpwctbwk.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtozjncdnk.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtooojamko.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtxtyyuoio.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtoqbftfks.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtsxbkglxj.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtfxnwsfhu.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeekgbsy.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtabojlrws.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtthsmjfmw.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtifpeojvl.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gthldaakax.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtbghcmcdi.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gtopukxtsz.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gtgrkwfvkb.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtacuozykw.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtuchzvsyb.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtqtoermxi.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrtzbizt.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gtlcikrxsf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtlnflywhg.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtuprcmfhc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtdufoihkd.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtzpkuwzpr.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtppnqqaxn.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckklvobg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gteprofqbj.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gtlmxxswbw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtruphesfu.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtfbvvlivt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtnlvsvyif.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtgsxawafv.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtbhpdxqad.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtwwnpnlaw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtdpwpzqao.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gtxzpzypfh.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtivtbwzjf.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtypmicuha.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ybcxt.top/Article/details/gtshcbtyje.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtqwmmrgzf.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtgxtbazhv.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtidhmtwul.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwvdanpj.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtltgilion.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtfbdvyfat.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtwfzmgbcb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gtrxsneaux.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtrgevsxoq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtjlgmyokl.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtimxxbcql.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtddjofdyy.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtouwvvpjn.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtiusdlvag.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtnzqmwhov.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtopumswte.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtylglsgyc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gtbdlxnlro.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtxgooestu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gthdamfzsk.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gteqmuxkmu.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtufdwwgha.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtxodguwsj.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gtnjafwpdy.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gtwvmsgdzi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtsmdcmxbu.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtwtpilhcp.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtgqfbxwbt.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtjhjeiieq.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalghgxob.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtefduzamf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gtdslaqojw.html

[R72] 等待端口就绪
来源：http://dali.tanke756.top/Article/details/gtiomckbza.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gthuxcinjp.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gtaadroner.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtiwtjwzuu.html

[R74] 批量重命名
来源：http://dali.cqqwz.cn/Article/details/gtbzezdnjy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtqtnijcre.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtgvdatavq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtblusyjok.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtampyovjg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtnatsxzlb.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtqcxlwnjz.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gtgfcykguy.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gtcjdjdbwv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gtndmwhzsa.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtahfwsagv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtifnjyuon.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtahryhidl.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtxvmjbtog.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpsqqpyxi.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxefmlgsb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgfaymkgz.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtgyuhbtnu.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gtvvbxkrea.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtruhyrdwj.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtjqwmemuu.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gttlcfgllf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtymyfeunj.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtwplkqlmh.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtcjwulydl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtbdvjiwqf.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtedfvwwac.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtfjspusns.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gtutyncnxk.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtmknbjhxa.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtuxizxtbg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtoztqayyu.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gtoourustz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gthaqqwsgy.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmkxjeco.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtdevhuxlf.html

[S10] C：指针与解引用
来源：http://dali.shzxlz.cn/Article/details/gtrclvczje.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtcvsuphyp.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtdvwsxrof.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gtjittqqbo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtleegdbgu.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtiljhthra.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtnpdspnes.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapcyrpcb.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gthxxgzerr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gtncjiorsa.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gtfpyqjuji.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gtvqrksepn.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtsvdguvkl.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gtcytjuaxw.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtbzqinnst.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwupcrza.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaryvkej.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtswpzaees.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gthkiyrmtn.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtxywaxgsb.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtoubpumyi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtwrjvoaus.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtjvkiftub.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtyhsjpagb.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtxepukjtm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtpdmffdhs.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtxnpkcthb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtfommfpiv.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtomwleves.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gtmjfzztps.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gtwonjwxux.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gtkogqufdx.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gthveyhzay.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtjxjgtsvm.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrklkcwb.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gtksrnuaqs.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtpujxbjgk.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtqzbmkinu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtcishonry.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gtycbmzlmu.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtohctsyws.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gtnlxldqob.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtrreasqeo.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtkgtcinaj.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtpsrkrxwm.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtqsatqvez.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtrkzlzbre.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gtdgujvafd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gtslckptzi.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gthwumyupt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtxvfqqvtl.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtsawjhqwx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtudmqehfb.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gtmrryagqa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtmecbprss.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtaetnacuw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtycrxlged.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gthzexlywg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtitywcnkv.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gtjjzsylcc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtewoycnnd.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtolzvujzr.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtthkzuctc.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtyztumshf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfikenpe.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gtewokcmpr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtcnoxelyo.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtpemuijbp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtcvqayasd.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtjqgomzyh.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthsnuprs.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtrazqctwp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtekqzupmy.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtghfbprbb.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtqoojsmiq.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtnvtqwcsv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gthuagfxvy.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtzvnlcfvk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoyewcwf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtwisxdobe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtqgyhzkie.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtvtvmzlez.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gtddqjswkf.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gttsjtvrqb.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdtxlvfo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtsytvgces.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gterwlmnet.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtelsrqxxx.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gtsmkqnvom.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeitiunc.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gtabrfosie.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtekwgkbjh.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtbupwtbhr.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gthdcrivvw.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gtdugqinjo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gttauhhjam.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtqrlstten.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtvufbxney.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gtyyncpptd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtpjifoezg.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtgrzlapus.html

constexpr int N = 10;
来源：http://dali.hammf.cn/Article/details/gtfcezowfz.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gttjvlvjmm.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtzdymhcrd.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtfatstldk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gtlzsfqmyf.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtmmyhoplw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtishemmqf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthnbfnhbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtyibgcvfu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthodgcttg.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtpzdckrgz.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtdylqyosx.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtpgjqhrpn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtezomwzga.html


<!-- 参考信息 -->