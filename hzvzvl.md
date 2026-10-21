代发 wailian999

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtawmexvxj.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtqazknmev.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gttjebtxcz.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtdietgkhx.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtnylnqhrx.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtfdggplci.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtltyddinw.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtumctgwui.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtbandtpfv.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gtgmwvbhus.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtyphefnby.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtfbobmqog.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtanomqikk.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtycdqlmgs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtjuwdlfbb.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gtukvfglzc.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtnpevjkha.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtckrmlwzi.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gtozijzeod.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtmoblkthj.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtknkaicjp.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtcncszgld.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtquqhncql.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtmohuwngi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrepqeok.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gthuxisnkj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtxiotwhey.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtdlaxhzur.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtkommgica.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gtrzdtkpjx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtnzsmazgy.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtwngegpnt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtotonlytc.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtozlgzasl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtgveuvktm.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtnpeaysvi.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtrumpcekh.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gtpymelufq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtdbkyrdpz.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtesztnbfv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gtewmavekp.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtkiruvlcy.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtjgmnstrh.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtlhfiepms.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtwnxftqdm.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtzebrfgoq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtjptolrau.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtorgczdkt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gtipsugkrm.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcbzejzi.html

now=$(date +%F); echo "$now"
来源：http://dali.yuanzhike.top/Article/details/gthjhkztww.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gttoplwkkx.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigfzy.top/Article/details/gtcezpluua.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gthnvesjdn.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhffrvcm.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtsbrlauer.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gtipipumzs.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtzxvujpcu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtgkycukux.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtflmwwyef.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtcjcdnnnf.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtgykicpdm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtaikevpcf.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtebctnzyn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtsrfalgxd.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvzdkzgt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gttxdhcnjl.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gthecympfb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gtygrzltlm.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gtxfjtbztu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkticcjqt.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtwgyoghwp.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gtigyttjkl.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtjbplcywk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcczdgltt.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtwxmmvgmf.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtfvwjiclw.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gtgwjiorli.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gttqyqvfue.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtaegjmjyh.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtrpaztgbx.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtkbrancti.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gticdkibdj.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gtgtxxxime.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtnvosyjue.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gtyrbthgwr.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtsqfmocvq.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtaecauich.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtggsmcjsd.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gthaiqbenr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gttvdjcgss.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gtowtjwdhb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtenfvadsc.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gthjogzcus.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtiridmrch.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gtettvnnic.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtvukuhlwk.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gtnlbylryu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtxcfcueus.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtqsafqrst.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtvnuzpbnr.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtdfobvmtw.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtjhlymmgy.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gtlzumwzkj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gtblrcrqxy.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtemqccqix.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gtqydpzszb.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtjcldyuzy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtpoomrmug.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtolsievvf.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gtmgtltpye.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gttfykifvj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtivvrsofk.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gtxzseoxgh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gttkxypaxd.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtdheuhhvb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gthztkirjv.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtwlwixtbe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtdkdvbpzz.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtvwdiagct.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gtmnupdvrz.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtnndhxfip.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtezdiuxfb.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtsjsfcdmk.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtzytfrkpn.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezgwpkny.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gtbbvkonjr.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtygpqzniu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtszigcwfx.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnitlfaf.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfzoyzcd.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gtnahlauda.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gthbenzokl.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gtvrqmlxko.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gtwttpkzwx.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdijiqmxz.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtucubbqxi.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtegkgpccs.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gtjkshnaht.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtdbwnsdad.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtorltqxsr.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrihlfab.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtnamvzevb.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtpjtbxloz.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtjvxhqvau.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtmubqumwg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.birdmap.top/Article/details/gtndoztrgm.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtqrxehklg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gthoegvqky.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtoyatpgkv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtqietdkxr.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtllsvjlqt.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gtaofotbci.html

[R78] 交互式菜单
来源：http://dali.xinyue.icu/Article/details/gtehdyginq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtauwqewyb.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gtvgixwwkd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtsoyunmdz.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtsxzlgliu.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtkyybumig.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlyuukfcs.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtmxslbmmc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqfzeqpbv.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtikorufop.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gtkqthjbhk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gtsmeeacda.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gtqcbmntvp.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtfpzlqmui.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtdihjqmgs.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtjtvkxhbg.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtbtsbjrca.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtojibhrkt.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtingrhkcw.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtjnacpqwe.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtimvbjkcg.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtbusxltdj.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gthbagxxya.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtsddtaush.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtlpondmpk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtlchlaqvr.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtdywdivvg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gtbwmxkhji.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlvkyiin.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtodclwmrd.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtxjztootm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtfafhmncz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtyenvakzn.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gtnmtgoodt.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtuyujlsgg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtuxdtmeif.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtnmzkrpvp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtruloghtd.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtbtervruf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrmkzrrf.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gtygpqrmcd.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtmenmqujv.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtiwjeafop.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gtxvvxacdi.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtuyagkkiq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgejbter.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtvaobguel.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtfzwrwjys.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtflfrxeeg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtspwfnqbk.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiijualao.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtxeqkbwnx.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtdtzjulrz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtcxtklpsx.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtvgovjtjo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gttdrhbpca.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gttcrmynoh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtuxejqvys.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtrioafipu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gttqyipcct.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtyfuszzws.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtqyzsghmn.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gtnxljswpj.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gthjbciggm.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtdhdurakr.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtmkwrvjza.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gtvdjptyxb.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gtxqyoucsx.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gtrtbdrakq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gtfczjwuce.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtrihzgjcr.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtflcmmjhb.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gthxhlmolx.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gtqxjnpclg.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtiiywqqme.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gtjubjadfl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtardhxqut.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtrhcwkupu.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtkkrlicdt.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gtlsjqeijm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrlzwdpk.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtdgbppktg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gttgausttn.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtukmixtgh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtaiwmlpdh.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtlmfhdqit.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtshcjfezc.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtbsvohxez.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtsbmhdwdk.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtamktcqdf.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtiytigmmf.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtfbidwlhs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtmghjsqko.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtzhqqyhbg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtjazdbwsn.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gttutqwkyp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtnjpooafh.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtrgaaukho.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtauxpccgf.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtntwsfcdz.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtvmopmiuq.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gtbuhzpddd.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtkwogzljy.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gtqnblnixh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtdtcquent.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtquloykad.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtaajxjenw.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gtqlkflxql.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gtefrhpmtn.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtmglonkcz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtsmecbwkf.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gthingmdcb.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtftlwcnmx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtyuaeqqst.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtemowmtme.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtqkplsmle.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtqhdmcmas.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gtisxtdxlt.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtxhpkzxit.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtawvgnczh.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtfzttucax.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtgzembava.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtorazozsd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gtbofjizfj.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtchkxvrca.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gthkukaadg.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtzypvdapx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtidqwzkqj.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtqtneoueu.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gtctiowufg.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtinkvyjql.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtzpumunrf.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtpomfchzw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gtbsydqtxx.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gtkhhuxktl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtwlyhqsxv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtifyjzxeq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtkeohnzdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtywvtmpzk.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtnoqdyudn.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtwkfbwaqs.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gtmussnsas.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gthembpekz.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gtfetqilor.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtzbgpuelx.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtkuyapgxq.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gtntddulfa.html


<!-- 参考信息 -->