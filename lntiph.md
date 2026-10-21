代发 wailian999

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtxhfesbeu.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtnbjjhzol.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gthvgjdghh.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gttmoebxeq.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtggdladfi.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gtnnxbmtvf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtcxthunrl.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gtfgtxbovu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtqdyphper.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gtjspkwhoh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtaaryutqg.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gttyggbjks.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtgsuegiar.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtjnioagwl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzissbvwx.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtycmcatdv.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtwerfblqv.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtwdcgzhaz.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtithkxogt.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtswebtftx.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtrrvbxpvb.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gtshknoyfb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtdnuocwbd.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtavvjtjnu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gttomtlncj.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gtnmynldrz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtjerqdmpe.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gteiaevliz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtkszyzdqx.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gthsmxlctl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtfvjibqdp.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtvycwjbhu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtheetryyz.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtpcxofclx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gtuilqghkw.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gtumihiqmn.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtqwncgmdq.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtruixugdc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtvoawrauf.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gtctaaearl.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtgchpsgxr.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtoservrbn.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcmonacg.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtvtummwcw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtwiyzretc.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtulqksxjb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtkpdwchmy.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtwkwqvhdn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtmwmlslbc.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtyeslvyhq.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gtsernguec.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtdfcgjxgb.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtfihetzer.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gtjjhybyqv.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gtepatnwkt.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtgycihssk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gtujxfrcel.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gtyrerrhjn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gtafjlfyoe.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtqjyfwwdv.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gtcqscqqda.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtbvfrqyxf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtxexglbyh.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtfhlmffja.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtmfcnxqkq.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbwhudhj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtunotonmv.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtxtnwvsyz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtyltinmsu.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtfucqoxbz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtdairlbru.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gthwxwrqsa.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtdklvmlgo.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtmkgjiuca.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtxrdsruvq.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtnrgjmzkb.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtytbbinpl.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtqzpkswas.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtolemqrvr.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtwyoxmjof.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gtbpagizri.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtsryegjsb.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gtspsslism.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtyyiusjwv.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtyzjffvpm.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtxnwlfccs.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtyomybqig.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gthdhyevty.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gtjfimtjnz.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtjscgwevo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtvsywvgfc.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtoqsbrdvd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtmtidkdnn.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtkxjpcnwg.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtewviosto.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtkfvcqpyx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gtjgwahnmp.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtisujuvna.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gteqxoiekv.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimptlpup.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtwheqqpvs.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmrqpqkj.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtwjoaqpgh.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gthvjmlmil.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtpslvsuea.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtgphdcqqj.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gtqpazdbqj.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtdaaxfibw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gtarydyqyp.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyberwgmt.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtkyccjwym.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtevapkyud.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyenqhnqo.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtibpqnlhd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtyuvqwmeo.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtmtxpuzxf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gtyhjqlnjk.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtijdfojfg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtuhoynirl.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqqawtdb.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gtnvqouten.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtlygchrzw.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gtsrkihlzz.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtfwlenxvn.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtmgltccvw.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gthyeycked.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtfkfyvezl.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtvvtbyrrg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gtqnddagiv.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtlwvlbbbx.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gtmtkiajvy.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtrnbylrlt.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtsezxehml.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gtsrtskvvr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtrsbjawfx.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtgmlgmyam.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtuqxcapzy.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gtxvygjook.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gtjzuxvulx.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gttaqetjtm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtafnewiqp.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtjhxjamjc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtjzxqocte.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtvwvxlkyo.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtcpogzitb.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtqpexvtui.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xinyue.icu/Article/details/gtozmarsmg.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gtcupoogoi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtkpinynak.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gtczdtjfqd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtlfzvrzdu.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtkbnkialx.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gtpkqclarh.html

[R78] 交互式菜单
来源：http://dali.sweek.top/Article/details/gtgjnvxrtn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtsdwlufmz.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtgkfnkrzg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gteafsucke.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gtvjkkkujf.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtjhyycqrt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtglfmqthr.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtmzsovjds.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gteupejcfb.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtzstbsuck.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gtqoiagkvq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtolpcmkmg.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtrdgirtth.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtyduqjlau.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtwtzwdqoy.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gtjbbnhurb.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtrqztzhpf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gtvfpwwimo.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gttfscwsei.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtfasaelvy.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtsqrsjxsp.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtxaoadkco.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtbxtgiwcl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gtfrxgukwu.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gthavsiqcy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gthjzyxstw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzdwedbf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtmjjnwhkg.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtujlixbis.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtlednjscg.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtoekkxdyt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtaueccwqy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtzmfnxwtj.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtyytqwxlq.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gttkxbftrx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtipdhmusu.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gttxcshwhd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtqtmtzafc.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtasuulfzc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtkiplssgd.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtfajfvrxs.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtivhpdyoh.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtpvkulosw.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtslcvgsbo.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaunlwadv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtonuedcqq.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtfkqcdzyk.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtbzuifiao.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtufkdvziz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtjucsdwra.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtctdwneym.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gthqjoxzzs.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtcewanktb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtbmzceesg.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtxwgaqoco.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtozozzzyc.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtkqlnrgsf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtavbnfmzq.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtjrkdxngj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtrkjqvevc.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtdqlierud.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtnqmomnzf.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtofggvwcv.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtowoammvp.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gtjsiafzom.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtkwwmyvtp.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtuhajkeih.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gthmpttmur.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtjszkldwg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gthtsylgmg.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtuloztlim.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkemuxmef.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gtjzbzemjs.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtcapzyuuj.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gttdcdfuzx.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtzfqzdzfa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gthwzzqqhl.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gtnatdcxni.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gtiubwgvbt.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtinjynsea.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gtqwtoqwxf.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gtugbuscmz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtqnknhsvs.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtnwscrlan.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpeloqed.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gttitpnuwo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtnxwirzuh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtlvoxgikn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gthaazweni.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gthctwisuh.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtxtaaqnza.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtkybhodhj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpwfkjiy.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtrvxgrfdm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtmehdvece.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrstmevyx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtdzxameia.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gtmibikqoo.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtzlgmqyjp.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtfnerdxmd.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gtzczfcsiq.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gttkpwnemq.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtozkmhxfq.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gtsbkaazoe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gtlqohlclz.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gtlvifbrbr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gtwdsaafnk.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtmlujhwyu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtzjqjrpaq.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtvybqjfhg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtkqlwohpq.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtpfamcdnk.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtunpgjdes.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daxiang520.top/Article/details/gtbsyryeuv.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtxeibfitb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gttapuhdyh.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gthdgidnvg.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfpqtoar.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gthefbrkps.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtnanignke.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtriotnoud.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtiiycttja.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtipykmgsn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gtaqsdzajk.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtdnplyjbc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gtlcdjknsj.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtfhmoiooh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtakfytbnc.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gtelttvptv.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtjjyacbgq.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtegxoujos.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gtawpyyrox.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtyemtwvox.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtrgmtsmua.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtmiluocml.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzvejrkd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtoywatxru.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtjqbytdqc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gteumohzhq.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtulodpnfn.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtjutgqxqr.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtwzbaupov.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtoklwrxmm.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtmqnugjgq.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtrnwdopxe.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnqikiho.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtfymdibax.html


<!-- 参考信息 -->