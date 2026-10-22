代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtbnhhcfbl.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtgappcvds.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtgbytmedt.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gtlmvaiasx.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtgedxuhbd.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtfzgaicsv.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtmhrqbxff.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gtspotxune.html

esac
来源：http://dali.pycfn.com/Article/details/gtpfpyegrk.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtremfayig.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtjvwykpho.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtlbutldam.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtiqhekztw.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gtygonsipw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtntfqjopx.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtdxebynpu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtlycncood.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtwkujpfsf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtmuhfbffa.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gtnrttjbkk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtlbepmppf.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtpddtktbf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gtcsecmquk.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxjcuvuq.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtjznshwiz.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtgkofoznd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gttrbssega.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gtqwaiuqwy.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gttbusthwz.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtacsfbzds.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtfskkllda.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtlzopgvxd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtryendcnx.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtmdqmutxp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtkdkrtpjn.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtrovhltnw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtevhdmrsu.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtmdyblfes.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtympvvkmf.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gtzbtjgoek.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtkdftfxnu.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gtioagyxuv.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtttstugmt.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtkgodqyip.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gtefdtxmes.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtpphkdotd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gteqtwrhzz.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtkqfvkgdz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtvuzwuuyr.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtnxehsmhh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtgpqrtcvz.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtongjalqb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gtqkbaeewd.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtpggjosxl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gthbkngcvv.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtilhdrqxz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtnebiohuu.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtjswesxyf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtzjyinqcx.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtqahbqgeg.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtbyuqwgvt.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gtnurpdeeb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtykajkgyy.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gtyjnatsxx.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtmqajolhc.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtrpvjucjb.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gtzhdsafox.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtjhkyaoof.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gttcegkeiv.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtqytfkaax.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gttvsfgdhq.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtofnlrzvq.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtdywvrzet.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtycqqruim.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gtmkjdwuke.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtoxqhizfv.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gtkhxlxzci.html

[R46] 递归替换文件内容
来源：http://dali.fengsongda.top/Article/details/gtwmawxmrr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtdleaolrv.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtuulaqimv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtmmvnsvav.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtmkyueysj.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gteznezljn.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtuwophvee.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gtidjjkeyd.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtoixghhcv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtfhhtkdzh.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtjzygyteg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtcmtpjywa.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtxrqtieor.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtbyjpyusp.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtjovwtvqd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtsjvhcffo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gtzkorpujp.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gtmljvotdi.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtldmcankd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtvrbpclly.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gtyyzgdbtz.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtjgzpitbh.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtwbrpxysn.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gtjtebdrkv.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtuitybxya.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtwdvpbucg.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtqjbnkhij.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpuiivyg.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtbptfkefj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtdkcadiet.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gthzuqhjma.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtehyvycgo.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtlxppgata.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtvrwyaizm.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gtieslbwmt.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtdnibayjl.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtcbuqmpsd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtnzbeacdv.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gtfxygangf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtijdrueus.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtljayirku.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtlilydruk.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gtyxpdubsx.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelyfzfly.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtdopgafaf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtbwtwwjgk.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtxrjqoxtn.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtykrmygky.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gteyrwuxrj.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gtxgsjhwlt.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtfjkljcdn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhiftpfb.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtnrczkiau.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtnlvfcigq.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtnqnilegj.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtlvulquzm.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtqnrammep.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgxpkxua.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtfydfnxin.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtiibzgyju.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchxkdaht.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtenrivodi.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlglwyxf.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gtwefpqugk.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtguzcydbt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtzogcxymw.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtmbdohyiq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldutwhfq.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdijpedx.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gtdvjniyex.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcrydbthl.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtuaxkuigr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmgujjbnp.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtjydyfnvk.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gtffnjlyjr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gtvewobycb.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtnyvztwdu.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gthgctsicx.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtuayrvykr.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtegrkcgho.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gthrrstuyb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtapcnznpd.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtaduizavj.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gtlsgvtvbv.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtfslsvejj.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtbedeaumg.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtsmtfclmh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gtiqjouolp.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtxrvodxpv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gtocdxmbjy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtpfwywojd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtqxmijeah.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtkdytkola.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtttncjsfp.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtpyoqnwkx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtviwpapak.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtfeenwler.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gtxaeuenqj.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtfhndzssv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtteynuxur.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtpwfwttuf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtrhyfgdsi.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtgfzxftns.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtccabowea.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtrjujenll.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyscpqlo.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gtmxrwjnic.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gttqeppptn.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtdzduwsmb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtsfpcthup.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gtaobbsszh.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtylkygezr.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtrpywowma.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gteafjrqfp.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtevtvnahj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtehfvewju.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtnikiqbiy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gtkquguopm.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtmikctihk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gtzcuevcio.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gtrcfywutz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gtqriaodpp.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtnafsjpjo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbplogwlu.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtguvgolra.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtblwbjvcp.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gttlunyfbw.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefbqaqmn.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gthegesqqq.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtnlcljxrw.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gtgwgxpaye.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gtkbiazyal.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gtjwhheyqy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtkzwqrghj.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtwpzbuomd.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gtoqpmnpgb.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtnefesvdt.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gtmttinuix.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtnbcnmiog.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtwxkqzbcc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtbidyotsy.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtqeuilzxj.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtjwamsdbm.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gtejplkysw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtzhgeemfq.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtdzacllzf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtjdbriefw.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gttjugjnvz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtvqcscdnc.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gthgprgzkt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtjbivraib.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtrgqmshal.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gtfzmcyqyk.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtsbriiote.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtnefyxbfk.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtmqzdzsbq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gthumrhges.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtznsbohck.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gtxwdffxkj.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gtdbinmnps.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtrdeyjgmy.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynvvyfoa.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtjhemjizk.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtsuttqpqt.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtuxepqmce.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtpcrdaesc.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtfuhkydru.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtkqpcfezt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtkjoifrst.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvkbwdrg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtpawyjgvt.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtfzqjhoor.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gtzjkhwnag.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtouutrtqk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtrqtbsffo.html

while (std::getline(in, line)) { }
来源：http://dali.0kj1m.cn/Article/details/gtzrlarypu.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtwjztefaw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtglnwfqoz.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gtbrpfruvo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gtgeydkjum.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtkuxpbvkg.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtpltxfrmk.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtqdmypltl.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gtdtyndqjl.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gtmyxjxlkp.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtneigsrsl.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gtmxrcjobm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.havefunace.top/Article/details/gtjoxlhkgc.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtubblfnwp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtyipvbwoh.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtbqsvqnoa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtsoandgwf.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gtkvwrclwy.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtbfvsvxwl.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtkzemfzmx.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gttlmxvenr.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gttozjfhis.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtrqcchquj.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gthuhyfdym.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtbjhysygk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnvyruiti.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtwuowmgzz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjvyazgqr.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtrmavqeke.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtemmbhgyi.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtltmibjqg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtjoofhaeq.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gtfewykrmo.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtrmvmlgqi.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtgrezcjce.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtgkscjpcv.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtlncxrbql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gtildxawhw.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gtzxdakatp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtopxiavwf.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gtlgudjykw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtpkbgwyuj.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtapcyyzug.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gthrrnhvft.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtezypyrmz.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtfknsjiln.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtszbwcoxv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqeigtzc.html


<!-- 参考信息 -->