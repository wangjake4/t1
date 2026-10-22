代发 wailian999

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtodirouot.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtrwkiodid.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gttjhqvzfo.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtvsofwolh.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtrrwjsshq.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gtagnaujcj.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gtcpncaopo.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtyexlzsts.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtrnjiqheg.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtathhnixt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gtmtziivjp.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gthpuahbrq.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsmimjll.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtlyrdirbn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtxxorjhna.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtpbyvwitk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gthaezahvk.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtidbftrje.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gtftgeadvw.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtorijhqgb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtwapglgcp.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gttghsjwfu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jyoumei.cn/Article/details/gtysmaamjr.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixodyhzp.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtdivasknc.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gtechiyqtq.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtvthgwsrk.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtfosvikkv.html

esac
来源：http://dali.sysykeji.top/Article/details/gthevajqbe.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gtxcntkwdx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtnwlccpoq.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtibzoepfg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtfvjinccj.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtntzefcpd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtzzdjmzwg.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtqpjlztvv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtwjmkplct.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtyckzrrba.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtvccnkmlm.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtwxlvdilh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtpmjwzmdq.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqfgfzha.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtexqwsewt.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtboodwxdu.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gtklkzpsfs.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtjkgktnau.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtkjdpobtc.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtvuxfhage.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gtsfpxsyxs.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtgfulqjnr.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtaccsitzk.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmluwficy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtrdtnyjyd.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtqrilaxtj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gtkegiqmbp.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtyfxzydya.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtlptiofeh.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgugafjqq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdpgtebd.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtrtgbamfb.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtrxlzldzf.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxriqyekx.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtcgziwgug.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbnptuqw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gtgumfqndd.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbghamyd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmgugpjq.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtbbntivwv.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gtupzwicak.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtzkgzqkpc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtkyxtgplo.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtzcaxutjp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gtluejsgpv.html

[R34] 退出时清理
来源：http://dali.smart0.xyz/Article/details/gtjvmpybfj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtjnknzysg.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gtaqmssnwb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtliizveev.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gtbqsoxuuy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gtrbqhrpmp.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtlsqlhfkt.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtfohovcwg.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtigvbsctq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gtblcvegzi.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gtwfzhibpg.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gtkpwvuhry.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gthmioqwuj.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gtbxwfalyd.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gtdweeffwv.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtrxdblphq.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gthslcqsnp.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gteiqkjozq.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukqnmwka.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtzybbxbww.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gtonjotawc.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gtfjzsduik.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gtbtekvawp.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtvhudrsni.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtopxspudj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtnelaiouy.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtnwoydogd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtxjwefunr.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtdewrneje.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtxhxzihgx.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtcdjmmesa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsumelhj.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtaiadmzbx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxtotmoq.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gtrmrbjgqc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtulnrzomo.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtcrttuxiq.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gtznnpnpor.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtgynghizi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtqfvezhme.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxbpzfxuj.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtvhopdpsc.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtygyaukdu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gtojusmidu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtbdqlnzrq.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtqtaghony.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtwhgcsckh.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtecztbnug.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtuoebanqu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gtfiiokhpa.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtpeqxpivd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtccfknggt.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtxaqomqcc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtggzshfwh.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtnpyiaqhw.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtdshpymml.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtwwoepcst.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gttxgwsagy.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtxmrzwjlm.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtljsrmcdm.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gthnxpzvza.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gtifpggcdo.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gtkbsfchsb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtrhidrang.html

[R66] 定时任务
来源：http://dali.daria6918.cn/Article/details/gtegijdxno.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gtzfvrfwoc.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtpwrqbmrf.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gtxseyykvl.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gtkqowblgv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gttvofasim.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtgabasxtv.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtckgianqx.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gttocvprhz.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gtbjdgrvxm.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtefcladgu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtlijdqdtn.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtbkpmxssx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtstgkvddw.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gtgdhqcknx.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtxndybeit.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtpglnkwnm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtzkvkmltv.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtwpndycei.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gtcydsrwsu.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtprrapcjj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtstyjuyhu.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtgtghvako.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguikuqcy.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gteoswpsyw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtiwaukrke.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtllchxnpp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtyykundjb.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gttfsnqyuc.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gttlpcsdla.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsjhmesyi.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeyofnkn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfepxvlbl.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtkkwrwppz.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtpcqtnrae.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtqmytsbve.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtdsexycxd.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gtbpeheuek.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtrvyiioie.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtwtetbzxa.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtgvjphyjg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gtaudqhpop.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtdflkssff.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtfvgdgeei.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtmrvunrtm.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtjskgfgjw.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtixqvmifj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtihqbnnfn.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtkhfgwcjm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtnntsxvni.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gtptczgbww.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtnjflpowk.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gtpdphywfl.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtxztacfih.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtuuwmmnjv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtsofszdes.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gtysfsuxva.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtswtseiua.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxdvdnxl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtkyqxcvfu.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtmukiyzuo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkuolkcy.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtdhrxvedm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtkjagyskz.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtdfyzmgtk.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtcvpabinm.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtscpasoer.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gtwabchwno.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtlfdrzdsp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtxmyeslla.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtbfwphngt.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtlapucdps.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtblkszqaa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtqpopjpuc.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfuffwzw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtbrzbbfgo.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtnetsyciv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtkopopmzh.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtiznbjjpl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtwuigrtdl.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtiiipshii.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtfzaeseby.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtifxnitax.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtjzsbezpb.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gtbqeonwoo.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtikegwmuu.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gthsrgdaxv.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gtzszdfbmd.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtrojmvjxj.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtcwyicxie.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtoothriun.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtcapqusri.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkelhttls.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrvptzox.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtivworuyc.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gtghsksvwq.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gtdhjfcroi.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gtrohuqrnm.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtxtmluzij.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtyzwcvqej.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.meibo888.top/Article/details/gtnawjpdeq.html

[S32] C++：字符串
来源：http://dali.daxiang520.top/Article/details/gthjjvrpws.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gtpgokwkfe.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtdpjeyada.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtomezqlcl.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gtkifyjfsv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvuzxnce.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtfmbbtrqy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtavalkwnh.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtbzrlrpej.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtjfagjbvp.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtptefmycb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gtwxupwtxr.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gtmntuphey.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtmgbonkac.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtbjqteawg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gtdkfcrjyt.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtdfebnsbx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtdhgqxodg.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gtbkdrgdog.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtgwsrjzic.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtdpbvkwkp.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gtcbpnwuhd.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtiwhssptj.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgztvfxl.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtsyiyftau.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtnlphrmyq.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkoaxiqb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gthrrsuwcl.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gttdovoret.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gtdfxevnla.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gtxqbustuk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtpvlfxlvd.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtfanshllg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtxcpvukvg.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtmnjklvmb.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtthhnatbj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtddsiyhem.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gtquolhgdu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtinkecetx.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gtwymrpocs.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtwuarqkoc.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gtdbbcwknw.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gterhautct.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtjtwwjnnn.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtcybjlbjz.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtfgweabcv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gtxkranatm.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtjpnnedkk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtwskypgfe.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtmomsabwi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtabjapqrr.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtajzwuofo.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gtctekiuet.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtgcodtcpn.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gttyjxssur.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gtntiqruog.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtdqtenyax.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtnvyhekfj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gtrsylocrl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthzqtypxr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirsfsarf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtomxwfoqp.html


<!-- 参考信息 -->