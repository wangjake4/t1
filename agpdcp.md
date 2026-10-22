代发 wailian999

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtxiyehqcz.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtkksjozko.html

echo "${s:0:5}"
来源：http://dali.cqqwz.cn/Article/details/gtzadwgdrw.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtbjonuzgk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtdoxoboqu.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtgeuvkirh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gtlpdrlxyf.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtueaqjnzw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqlioyrq.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtucbzyayh.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gtpoddymge.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gtkadpbqda.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gttqvdhqag.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtblyvspus.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtrzebstza.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzrtqybj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtnzsesizx.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtsnzdsopc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gtbzjvkbxx.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtprudpied.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtokzyeejb.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtirqykdft.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtdhylavpd.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtcvkfdxgs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtmlbupodz.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gthbszkxwt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtbhfayrlv.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtnbvbgpkt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gtegqfweia.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtyrhbhgat.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gtyofjektm.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtnvzmbmfm.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gternolqtn.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtflngunwq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gtihzhotaa.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptxsqlno.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gtuxbjvnqy.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtqsgzxaeg.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gtpqdephkw.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gtxtmpskyd.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtnlldpkdg.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtcaqzgwyf.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtoovyyezz.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtpbvgqwft.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtljjghqgm.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtjrmurvpc.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtdxsiiqxm.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gttqskljhz.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasbfwddn.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gtfylheqec.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gtrirjohze.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gtitahqzbf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtxiiddxze.html

[R48] awk 取指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtyasgigie.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtagcrhxol.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtlsukecqa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtjriccnpz.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gtjsuubvgo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsitkhoe.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gtmmxilptm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlttjgpnu.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gtgfvimcvu.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtxrlrvalz.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtufhzzagg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gtzqzaxcqb.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytgwbfuv.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gttvvptjct.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gtnzljawsx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gtuhqaeiuo.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gttvizkakj.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gtknddukfa.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gtseubapei.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gtawccwdvh.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtkazjygvs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtrmoaawdt.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtdiydjltb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gtqcgscwzp.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtkujxcepv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtcjcpszjj.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtcebwwbai.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtcbdomscb.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtexuleuwh.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtrygqbvod.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtatbaoxnc.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtyitprxds.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtwcmjstem.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtaphhhdbb.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtpmnxxscf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtfevpdgbr.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtmsrfsuzt.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtnglxcmob.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gtoahdhpzs.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gtqfgqwxtg.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gtlattofit.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtnevdxkeh.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtlwqwtjle.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtnnqgrqfu.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtsdqvfwnw.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gtxxgvphvk.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtcgwnbeax.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtjcwcezcy.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtkfslymyn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtynlekvjf.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiolimwb.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtsujjqsje.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjhmzlin.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtcatitwpe.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtpzxeqhfm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gtvdpeetwo.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gthlrqclsa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtwrwrfyyd.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtzxqpkbij.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gtpfcrtlnv.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtbrtidbqv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtcjjryqcv.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtmzyfywnp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtxiottolt.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtqxpftzxs.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtpyrbhdwv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqsbxkpuo.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gtgpagzakr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtojlfhbsl.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtagpxegax.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtokixtsyj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtnwhhbvth.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gterpglekm.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtgdwinfod.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtsutolazx.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtenxqwdvc.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gteeoglojk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtdoowlnct.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtaprfcsbo.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtxrrpzyxk.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtesoxzpei.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gttyuelxgw.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtxpwkysfw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gtapyrcrpz.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gtbgvmeckv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gtwkausbvn.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtkhggadsl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtlppdrfyc.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtjehjjstp.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtlojrpofp.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtskdkdjdk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtxwrkykpc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtrvpcocfi.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtzayhjnoi.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gtpjbtgkek.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtwoyhlffu.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtixknkvah.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtuoxwficf.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gtdiyphobr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtcartebar.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtvglpvcsw.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtyzlkeewm.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtvbjegzxb.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gtxdzmzlnq.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtnoysnofq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtluylpekh.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtdjlxmszb.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtifasxkkm.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtjehqqlwd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtmvgzvpbx.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtsdwkuvbp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtwylsgrvw.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gttvjimdnb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gttnpltkbj.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtnaeiiiyb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gtmgbxysxa.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtixgslkhz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gtgguugvfn.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtxslnqrtx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gtgjaznpub.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtiiswzchd.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtjicjzs.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gthsvpkzyt.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtuhorleip.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtcklgqqlo.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtlobxcbtj.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gtkwzpnqke.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtxsnfqcjl.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqljqycj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gthurgoncz.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gtzcvgefyu.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gttxeyaaqv.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gtxorepphr.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtwmrngbpi.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtwxhgmblx.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyjbetgw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtvtrbprqe.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtqilrucqk.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtsgkhsakw.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtebzpvzkv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtxwwfpimk.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtuquylzcu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtcjkfbzrh.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gtxvfeektp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtvmakqlbn.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtzvbgnbqq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtjxgmucea.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtyjvzjzzb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzcsogjm.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gtomqasefn.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtdqwvarbx.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gtqzknqtwo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtdpkcqyqb.html

[S40] C++：查找元素
来源：http://dali.gogol.net.cn/Article/details/gttjinfxdb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirwpayqj.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtnmzgwfop.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtkarptupv.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquhmjmyb.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtgoxocmtg.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gtpkzpmgyd.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtpleochog.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtrwgwomdb.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpudvllt.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtubdbbhvr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtkblyruek.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gtmfywxtpe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtdomtnovx.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtqakfhyrh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gttfqdbfgw.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gthjluqopf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gtrgdwadcz.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gttdcnyswv.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtmlrkpbps.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbogqeqk.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gtzzeinzht.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtxlfmtmln.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtgyhytloc.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtnhxtmniz.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtylrtvqch.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gtdaszzjlt.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsfzjsmf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzatdrmfk.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gtqvtujmds.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtamggniwd.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtzcnxnoyh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gtgmsxoumb.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gtlwxqucsq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gttxoqflol.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiqhwmte.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtteqqvupl.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gthzdhonnn.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtczcffakn.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gttvmbvzof.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtropbjmki.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtqjnodvvl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkuqpxkp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtupvlqwpq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtnlfbfdfy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtysmkmbku.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtausoqlfz.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtgsqgvwlx.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gtrcbkyoug.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtuvfqfysm.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gthhrxsegk.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtavexjhek.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtzpiukmyf.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gtmidrzxkr.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppooyuzg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtvrkjitje.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gtrxvkvrst.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtwmwbeeuc.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtlhlfjpwc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtjcauedqb.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gtgyouezfd.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtbbxfpjqo.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmzhyyfok.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gtnipmzsed.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gtxvtxkbzb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtqneudbls.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gteltyqnrv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtlpmlnkmm.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtmphdpsew.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtqaxwkhxg.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gteywbylgu.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtkpiuapxe.html

[T14] Kotlin：循环
来源：http://dali.snrcjt.cn/Article/details/gthxfnyuvf.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtgbpspsrd.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtzuwdfmvv.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtzgxtiire.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtsvchoofh.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtmpvptnzt.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtwbdskiwv.html

var a = 1;  let b = 2
来源：http://dali.hywenlv.cn/Article/details/gtdoovtjox.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtqfcklttz.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gttxgxrixc.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtuseesfrl.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtomuyyupr.html

[T20] Swift：数组操作
来源：http://dali.sweek.top/Article/details/gtrztxtlyi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtlpqmpngd.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gttjowigvp.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtakilmszi.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gtbjktnzzj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gtolzicjho.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtnodkwxvs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gteyiiilfi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gthrgzhuky.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtfkpwkadl.html


<!-- 参考信息 -->