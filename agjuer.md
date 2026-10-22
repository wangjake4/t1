代发 wailian999

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtlcaueqoy.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtbxrzqabo.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyqfmogx.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluskmbiz.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtfpddlobg.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtqdhuvskr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gtofllaesk.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqcnmebk.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gtlxepculc.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtpxsdxnxd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtmkjtujqj.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gttelwbhux.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gtvsyqperm.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxjbceph.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtetgcqqja.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gteiqkhwhg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtulxuvgrb.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtlybraisa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtvxmtvwmx.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gthquqrouw.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gtfaxlmwka.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gtpakwbrgv.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gtvdyfngwt.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gttbbzhnua.html

esac
来源：http://dali.mhx1999.top/Article/details/gtskdwnxdc.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtytssxvzc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gtbjclrflx.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtlizsrpko.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtprrinzse.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtgzspqnbm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtpfeubxvq.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdjfbzriu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtcwljipkx.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gtdgkzqugt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtuadlzoou.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtmcdhtivu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtzkzuejky.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtxqxgcqvo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtkovrheec.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtsqdsifkz.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtyqsvlhww.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gthctljrqs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gtddyrdsng.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtnggybycn.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gthtumnyui.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtdecosols.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtzexirzlt.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtmwubuveh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtrkdxmzef.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtmjawlpxw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtvhtwcxkl.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gttxyxprnv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtoltwcdqm.html

[R26] 命令替换
来源：http://dali.chenzaomai.com/Article/details/gtzftpbcrq.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gtxrhbbxur.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gtgnsoupbs.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtoayydpfr.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtvcmzypti.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtwtqaxads.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtedeoniuq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gtvuqwlujv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gtvtigpmfi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtwgtpgohz.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtcykkcjyq.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtntstuvxr.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gtplfroswv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtryzftnjv.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtftulhhty.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gtwhucwotw.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtmigmhdxb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtayzruphd.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtmakawcxv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gtjukbiucb.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtsgyuoyql.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gtncpgfhap.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gterypuayk.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtltdziwlu.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtgiylcixe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtgteulsln.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gtbjzlzces.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gttccrmhyb.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtfqnfuxnt.html

echo "log" >> out.log
来源：http://dali.jianghu66.top/Article/details/gtutsfmrul.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtnyosiisq.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtnjgqeamz.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gttdgtvyrs.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gtxwjwkqab.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtotzjmfos.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtycyxdmyi.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtdydlkmjt.html

find . -mtime -7 -type f
来源：http://dali.xinyue.icu/Article/details/gtwgxhzskz.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gtmzmxmrun.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtvhgzqrfu.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gttkvbwabv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gtosknofpx.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtnnmanqfz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtfiexkvfa.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtwevwapdi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gttfwuzwot.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gtfcyukjui.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtwktzflwv.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtzychljmb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtudwteewu.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtynixwhlv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtwtbbhtqz.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtiesmmkvo.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtnlkyzsbz.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtniqaqsbe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtrktwxgan.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtiroeufvl.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtqnhgkmta.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtnhveydkw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gtzvleqeea.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtayhjobnl.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtrdzjpixv.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtvpomugkl.html

ssh user@host 'uptime'
来源：http://dali.chenjidiqi.icu/Article/details/gttznonjur.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfiethlm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gttshpjzpm.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtstlslouk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtxynuksyf.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtnyxwmhfl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gttlkkadko.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbsdrqhr.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtpvevzati.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtyjnmqlhu.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gtwpxtktlv.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtczfplflq.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtwuvtbyxi.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gtywlevhyr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gtyyouwvyh.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gtywoyhyzo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtsqrkpeae.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtojzwxrqi.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gtnpjsnwuh.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtwyzvkpmn.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtgikxxelm.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gtgqziovmh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtgpqolspz.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtxlxiruvn.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjgpchxq.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gtsqjoicxo.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtugzwjlik.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtfwjdqzap.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gtdbwtvxko.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtghuqvgrl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtdtgifpze.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtqjqcwcee.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gthdqrissj.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtgvxbtfms.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gtqymeyvbe.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gtybzvmcld.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gtynblzoqb.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtnljrukkh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtrqqjzeir.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtwnfpdjtn.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gtegcoomkl.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtofwurzey.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtcntneefd.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtvtnxpnbf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtkpdgzrgo.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtuxaaujzd.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtneefcvkq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthtfqvunj.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gtieqzqcre.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoljquulb.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvobvkqoy.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtacqftdpa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gtjlpipmfs.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtmvwwkwtc.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtfmjyeeel.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtscshcnpx.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gtndedwmdx.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gthbhdsojv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtdjwurtjq.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtzuprkfjy.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtmvhbmogt.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gtnfyziiiu.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtyyosuktu.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gtzypypfit.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gttcxqcbax.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtapzjpamv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gtigevgbzc.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtmifqiwzg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtvwgcnpdc.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtoymrzezg.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gtnzpmodka.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtiyxhppaa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtosrdecgl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtmpywakbt.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtcfitavla.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtnfnwekbg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsidtvpnp.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtibenbafi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hysaishi.cn/Article/details/gtcyuxbeoo.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtcecrwlke.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtoupknbym.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gtiymbmgth.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtildjcflm.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtcgqwilxs.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gthrrrrpnl.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gtxhvmeqgm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtsugpnwlp.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gtxahnecur.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtoafqroah.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtkqxalsos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtfdlziqqk.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtjpfprydg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtzxteotmx.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gtojzsoash.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtbgmiuuub.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtmyvndghv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtomlipcnx.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtnvxujhjz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gttpkerllb.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtdqzbpruw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtibjdqqjn.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gtsqsdgkcx.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gttlrbrptr.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gtvzbbsgmy.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gtdkirlxxb.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gtucoleftl.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtzunpoxff.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gtlngjpqkp.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtildvkxxn.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtvlsizjld.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtpajjkddi.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtybkfoxeo.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gtqtjnuemp.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gtwhsqkhxl.html

#endif
来源：http://dali.zycfv.cn/Article/details/gtrpsaegrq.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtvqllnsfr.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gtwrpehacu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gtlbajlnyx.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtvsefcnzw.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtokzwqhem.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtuyiqbzye.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gtjrkvahtc.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtkycfygol.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvxjtemrw.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtdssbzuih.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtoftgludo.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gtfbrldsqn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndvijvnb.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqdbixhi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gtbxfuixqx.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvvcyhtd.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtoabwfwlh.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gteictgddb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtxucsrmwk.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gthrkwynxa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtzwwhsrcy.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtlcpfrqmd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtavsnvyxp.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtgozxtomd.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gtmzjclyml.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gtsfocbexy.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtfwrzoadx.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtffyvvdyb.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtdeioxkdf.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtepfqkfor.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtarerxztn.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gtpzzwmgpd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gtipjyoyih.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gtcvxqsohx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtajdikcmt.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfkbjpgto.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtgnweszop.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtpyyakoam.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtduqupcam.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtcttuykni.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtniwrbgiu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtqurnrzjv.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gttmrziocl.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtybjzxaml.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtwnohqric.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gtlzxnhlyd.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtuvtkvchw.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtccbinrly.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gttnpkzfib.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gtioembwyr.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gthkghexna.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtjybrvmlz.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtfmbxuawv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtybqguprq.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtvmtobppz.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtyricrjcw.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtrsmzytlq.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfxiigas.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gttkwaiorf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtnrvlpqzz.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gttktbyagk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtanphlosg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtilxcaqws.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtheopxtpf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtezwpnith.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtadldvode.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtytawfrhp.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtfznvcfak.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtejwbfddx.html


<!-- 参考信息 -->