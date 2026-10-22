代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnkaxlo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2detluzfa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2quwdrdor.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrxeumb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqksifa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeblztb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfaskyg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqqwdau.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzpownc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2avmwcvuy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecidmulx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdlsvsx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkpojvv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxbsknz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2urdioxui.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhqztzf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyktcac.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hngiexdp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uobzytud.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svxyuqqe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgomyhv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdhmxvh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmrvldr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbgiszx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqnfsov.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bwearsjn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrcfcds.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2htglnekp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hldpgrjm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqocamar.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaxlkyh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzlpnil.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2enzsrejs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaenmoo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2olpebrbc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2txdioymh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbijrqx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxyuyrd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2phyiekdk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2etaanveq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eknfviyn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ewegryjp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kyofetyt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lurdyfow.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjvvkzf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2epbrruwd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rnemsyzv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnasexoo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iobuogcn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeqewhg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fmntcpxv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sphotgzu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2idasmfhh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeapimu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzrnvzg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdhezeb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xjustqlh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2riqmkrgc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czqhxyro.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdonfmm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyaevbh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdweeql.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2satrkggp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdzilnt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhhovlo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoejmbx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkbctiu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2diwrtkoa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmrgdut.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwddoct.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pdovffps.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jharwzfv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yypuwepe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wejqxdmc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnfbrsa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2deowxmik.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jawvpmbd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uygbblxd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bzabrjxt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iwammcea.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eyutmexq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvbedvo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2edovgfce.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2plqyocko.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dhymhvfj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvomejfb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdyvcdo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dzylqvsa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaescom.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjcpmsn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxpwfay.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuesxcl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqawvyc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hprazdcl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bovyccdz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcggnyl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vavxdpzs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2acjantke.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2piqjstee.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjyuouq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ggecirjr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fcthoyey.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kulbvqhh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlaukyg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2oepbodcd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lxevfjpz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjygdms.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxuleni.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nlslrjde.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mojgaszu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aogmxqzh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wswvukfs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuoqlzz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idmbtfer.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbvnglg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxoiykp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2obeixhel.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2irbopsxr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2apugjwpq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqkgpeb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsmwbtv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgvrqtj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgudckz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nglzjjbg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzdhkae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmugiya.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hswdhwgu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfathsx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoxeapt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkjwwnr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2monnhity.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwpjmrz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uahbiftx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhrzwwl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lezdgdst.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2szmjongn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dagrreuy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bufkiblc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnqmljj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mpduspfh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nhucpfmx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgugsqy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeeoooy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2umplsihc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fepxghpz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uimkylio.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ortfriht.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edtnqnal.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cibajqnr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlojpjhm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwlftyy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnocnvfn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ducsiiph.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qunlbfae.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2quaiailt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vioygkka.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpixudn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aormrila.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyumihu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vrolzuib.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2golcteyc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwabtii.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcegvbe.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmfqcmr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qchxuyet.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzkfath.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmevzga.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mhntzlhl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjskjjo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oxudween.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhhctgw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqqgwxv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2khlnzlet.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvfhcab.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbyrhzt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsnasfb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmyaffn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aeteerpq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxniuiu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnksdzb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iazjkqnu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwjxfle.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nffikxzj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppedoaaa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vasuvrmi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrakgyde.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yghrfcbu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wdukxzqg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcgjacm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zaupwmbo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tersvcwf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbilnms.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjbgfhb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wydjrmrt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qoerweym.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfoarou.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gygvszao.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtqdflg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjdqprb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daxrafdq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2drizrpns.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cibsqpwl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2muombcdk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhihryd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lzftjsbg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2epxucnix.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ganlcnid.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wzheddpq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnwanmp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcbaxnj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jiptijby.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpbimrq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gldpvqke.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwiiuum.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwgrhqt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpwxgcx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwchequ.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrqtrob.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2svoiviio.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kijiqwat.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqxjlqp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dwunqexw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbicxho.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whcxswyz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tznjhfip.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhumtjyj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaywqik.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhqwlfe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2knskjzhz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zktuqbdc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgynbea.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnhgxab.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2munnhqpc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhaayfb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bqachlqn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpikeia.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtddebvw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hcipzgbm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzevsps.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvinwoy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bisezrye.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oqckvfxi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsaiiep.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvlotut.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtutqlrp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iizcdjyp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcohzhi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fofvwnya.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbbjqxi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vniptoal.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcqcihw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxtcpbu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyhswkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btutctna.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwofmlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaggvqd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvmyegz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqdzpff.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvjenhs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zriawssm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwwzeww.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2btudayal.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuaasev.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2atlkjokj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqbkejf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2orjmfjas.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xufmuprx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrzbkvb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsvkyfw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyhgoyj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2chjcdaxa.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgghpot.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znthcmti.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvgtgqo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2itclwvqp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iltiwxkj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqhbvlx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iklkefke.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqrvivh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbktxzs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2knukltbw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylswtlty.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhoqddg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqddfjr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzmqugy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2giducrwv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bazefmie.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtornpi.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsnjidf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uffwpfaf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjqaqjz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhpqakw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2roqugxna.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhsgtvp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuazarr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbyhjif.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoyzdub.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhjpupx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmgtnof.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2biqzwuns.html


<!-- 参考信息 -->