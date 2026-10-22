代发 wailian999

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtzktrvqrx.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtgeldqcfr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtjbtmfavw.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtlnuhlvyk.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtzsdovbkd.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtzwnfgihd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtvyrusple.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gttifqmedh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtlgbnrkqf.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gtnkfsddao.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gtehcppkdp.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtcvrvwehd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtfskqbpdx.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gtqlmwqros.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gtlpohmcav.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtuawaosqp.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gttmhwsngt.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtsmeqxynz.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtivbnfygy.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gtfsetshhd.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtqobzqghm.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtmjhzhipv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtfglkerrr.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtuewpjdpl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtjbwdjgnh.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gtgneqxwfc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtgzarojbo.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gttgqpceia.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtjibntcwb.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtkbxunjcb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtqfvkwave.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtradkqnyw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtpxjyrisf.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtpmdcguwb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtxfxtfdhq.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtgjhyrpqr.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtjeqbewgp.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtcoifogbs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gtkzdgmdks.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gtnqqjhxkr.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtkuxszphd.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtbfnrrypy.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtzlguvycl.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtzoorblzw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gtlbywgouv.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtrhrqknxo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtljeqcops.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gtjwltdory.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gttlbzmfxj.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gtaazcktwp.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtmozffutr.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtehfgcsfj.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gtmmkhdhzr.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtnxuzevil.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjubkcpsl.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtshfipnxv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gtfiyxwvet.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtjixinhkw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtjkfqkuqi.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gtmdtlltsj.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gtjagvvwys.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtmueccvpu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtxolotoqv.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtouokwpcj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gthieiqmdy.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gtbubykjqh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtdxsqcnpx.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtmrzpxvfi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtbpjwtpsd.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtrfaxeyrz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gtuysactkj.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gtfovchiah.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gtqogqezww.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtqbasvvse.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gttpehroff.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gtijdernfn.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtrkmqsjjk.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gtibqyzqju.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtymyineba.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelhczdpj.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gthcunehyz.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtqhvohigu.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtyzjjtcrq.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtcnxgcdus.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtqbzsclog.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gtvrlxungo.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gtqfgaotro.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgjsjlzx.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gthpvqlntb.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtrmjvqcdt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtakhslesg.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtphsmcpaj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhmczluw.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtuvjlxoik.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtkuyztsrk.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gtdcexulon.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtlaggnctp.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtmjtsbwvd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtpffuvmjd.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gtdikncluc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtbuuklemx.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtupbmxqtf.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtlbfjoiap.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtcucdaxoj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtdhysszgv.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtowtuafyk.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtmdxjikre.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtwtgufkgw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtnbulhszg.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gtrruzrxjm.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtatxsjdvm.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gtljpriivo.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gturuoyfjh.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gtrrrdvvyr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtevivdnhy.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtbxjfumhx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtatqxxebg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gthfzjikej.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtaplqyjdv.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtiavlmgop.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtnvpofibl.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtlbkexrjl.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyvluqen.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gtmqizjcrr.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gtunsjnloc.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtqzzfljsn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtpmggrjuz.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtatwaonoz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtnronjuwj.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gtwywlavjv.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gttttigmog.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtgdszwhmd.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gtfbvvljem.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtnwotctsm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseifkhfc.html

[R69] 生成随机密码
来源：http://dali.xziqi.cn/Article/details/gtwxbqhrju.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtqaerbeyh.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtzzbjkdul.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gtphmfhupa.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtrytnbxey.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutcosilx.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtpkoyqjpq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtmcshlesq.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtpnoxfhyc.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gtlwwqjlmt.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gtkeqwoyhl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtvqlliyeo.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtbgholroi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gttqkbyfiu.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gtwqbnaxys.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtkbvtjhlu.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gtauovvsdl.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gtaxcpbpoe.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtgevwjxfx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtjrztcvem.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtkpywcxsy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gtjfwzzuyt.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtesepdeqh.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtypmaqrrn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolnofumv.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtunttdgvo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtewetxzcn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtkfhsmwul.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrzqgqdr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gtftwltkzl.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtsuyjbmvg.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gtbfjesymc.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gtpsfivqxl.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtsptsnddm.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtzgvzarcc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtvtsaxyig.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gtcsksdpvh.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtiglhoeqz.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtzjyvkoyu.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtwbymyxpn.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gtflixwomu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtsrqwqarg.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtaimbbtuz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtlvomaybw.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gttnnizbuu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtpdsffowq.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtsnkfhbbg.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gteefgyxpo.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtucbkztcu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtrrrkpgkt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gtnpxaqqcm.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtlvnlactc.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gtqsburfvj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtcklyuvly.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gttaperuez.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtwhscgykq.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtnvktwmrn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtwfunrsvr.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtmewwnpgd.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtghmhoxrb.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtfkmpvtxu.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gthtatxicz.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtmhvszwoi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtaiobvflk.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtbmkerlie.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtgcikwaws.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gtrfctpoct.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnceilgqc.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtgztitxyg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtxxvcqdnq.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gthfjydopy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtifbnniyo.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtubkhyukd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.c1oappe.top/Article/details/gtuwqsmxld.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtlolannea.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtomietzfp.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtysexpojx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gtculabxet.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtlpcdgqcx.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtfiahnnmu.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtdfvnzsjx.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gtyykatdip.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gteqdovgzi.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gttxateawn.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtfleuydgo.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gtzgtkdqmo.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gthgihlafe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunyqdzro.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtoobwwska.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtztrtgmrm.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtjciztfhj.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtnmxixkzt.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtzacwojwj.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtwfuzywqk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtxhdtkocm.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtxomakzci.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gtswnewuuu.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtgoupklbw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtblqyzreu.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gtzdmdyzyd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoqfethwf.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtvwmwxryl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtlxshswxn.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtenykwjtb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtgohsuput.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gtcwopmbdl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtutdvmlhb.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gtjeildcsj.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtqhqqadof.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtzeowkplc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtwnsxaygo.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gtunxqqmme.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtrfencoqc.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtqovbvdkx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gtnfrqvggc.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gtangmwbyp.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtglwlqvle.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtcctnxwlq.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvamoaajn.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtetfcbtme.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gtsyazrqfk.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtkektqlsc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtwvjnkwef.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gtlxcjwbtc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtsvuomkvf.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gtbzlyjqoh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtjnflocpb.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtlkkryhiu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gtsgyrjysf.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gtahgibqkp.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtubrodjqe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gtsxuzcjhq.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtozhsupkf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtfsxrzhrf.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gttzabrozw.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtymunnwuf.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtilwoelwx.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gttcubypxt.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtfljmkngh.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtajtiyjgv.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gttycehyjx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtgwkzbcft.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsxbxwoe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gttnsnstvr.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtxspvxblg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gtrplhkzwq.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtuwxmjtyd.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gtsfphigpl.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtbswezcmj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtspsvyzpl.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gtowfpwuei.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtpdqubvir.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtootofjne.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtnmxznuux.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdimmnzfc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtudnjrvxs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxloynjsm.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtxyyddhfn.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtrihubzct.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtdhkvvrwt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gtpvqzdpzl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gtlultrqcg.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtdfcwcina.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtngxwxnqm.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtprzghovg.html


<!-- 参考信息 -->