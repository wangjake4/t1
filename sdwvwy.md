代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gt2pkxpgxkw.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gt2ngyzddho.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gt2keeqjaoo.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gt2wobrnegr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gt2aywgyfic.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gt2uckbnelp.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gt2vkaxncvy.html

[R27] 算术展开
来源：http://dali.jqgfzy.top/Article/details/gt2mecbguld.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gt2hnxmnybq.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gt2mfupfvzw.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gt2nskwddcm.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gt2ugfkjssu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2tnhrasjg.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gt2fusmkvbe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gt2cvrrcpqj.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gt2wjrmycvz.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpopgbpt.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gt2sarrsocx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gt2ixzmjgrc.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gt2oggkpslq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gt2oszjecsv.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gt2vgyvwdgv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2kogzrnyc.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gt2osnqesuu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gt2yxtgdvzn.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gt2xfcbfufe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gt2iepgmkee.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvhdvktw.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2okyyqbai.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2iqvhtjtk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gt2tdhbuoqk.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gt2gskaktbj.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2mmklwtkr.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gt2dryyqwvf.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2pywpgjzp.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gt2mpryderj.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmvnylxs.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2wmfnhzul.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gt2joxbehsa.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2auadkkpw.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gt2hhejsxui.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2urhafxsf.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gt2oiugkpcu.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gt2jpxlwdyb.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gt2gwfkordr.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gt2rpobknhc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gt2xevjmsok.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gt2xgfjcfwn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2cvywyajj.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gt2prmuuosb.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2mlpqphol.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gt2kfxponci.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gt2tovgvkzr.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gt2xuotvwwf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2fxnshwpc.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gt2dcltsety.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gt2dfdzlufc.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2fnbtoccx.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gt2yeaizbhw.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2gjqloixf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gt2uufljzod.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gt2nyxqfvsg.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gt2vetpiwgv.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jebfzgif.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gt2azilevwk.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2xhvkanhk.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gt2bxalpexe.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gt2vtmpcaql.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gt2rxcnvims.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alwkpkfv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gt2bdlgjeyv.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yedlgwef.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xagjgoqi.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2wfvffwmp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gt2ouzawexm.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gt2kxsuxjiy.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gt2prhpdjhf.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gt2dxdsgxuy.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gt2ccdgapsr.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gt2tffmmgeu.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gt2hiazdbwj.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gt2rivprwls.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gt2fzmcgsgm.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gt2vxinjefw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gt2shdmnwty.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gt2yewpiuti.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gt2opmxpihs.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gt2xhvktjzb.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnfrgjjm.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gt2vcfddxdb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.bjfxy.top/Article/details/gt2itssgjep.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gt2ckomobim.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gt2gkmjvgfa.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gt2kregbprb.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gt2cnpdcfpy.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2npkbsrgx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gt2afbevvse.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2dubhkpkz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gt2nktvyyym.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gt2ygsqiqgo.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gt2ejwxnsbt.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gt2vrxwlgzj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2jkedutjj.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gt2nvtmtbhw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gt2wlqvjost.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gt2qspsopyc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2zjqclbwu.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gt2giwwsojt.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbydelsv.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gt2cinnaozi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gt2bjxygvkw.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gt2qszggjcf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gt2qcpcaxlw.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gt2mhrgqzvq.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2shjpftgf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bvbkfkbd.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gt2wuzujsuw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2elprkjjv.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2gqwjbcuo.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gt2urrcnzew.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gt2dckalfms.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2wzmcycna.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gt2zwqokqvr.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gt2nizrranq.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gt2dsfptzcy.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gt2krudssek.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gt2qrtgnltr.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2yuxgwrzm.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txonllak.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2whnniwmr.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gt2nbyicvow.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gt2qdhcsedn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gt2hmqvoryh.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2pptrkoyh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gt2onlpnfhn.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gt2bubujhxp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gt2ihwonail.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gt2ixvuxmtt.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gt2jyabaxfs.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2ujfqmltn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gt2ilbdfduv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2puhmkkva.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2tnxpxocx.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2opepzpdn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2vvefzfwu.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gt2ilplljox.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gt2ozkkgcho.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gt2vwvdsgac.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gt2ncsrznka.html

[S15] C：类型转换
来源：http://dali.sweek.top/Article/details/gt2gitappve.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gt2oayuigwf.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gt2duezyuwz.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gt2nkafjwvc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjtxvvd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gt2qjmxmdqo.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2ynxzftiu.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gt2lqnqhccm.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gt2ghmbxghv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gt2kojxqfla.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gt2qipkljzb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2edfpsvag.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gt2qmtmshxo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gt2bjgefeut.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gt2gjhpytua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gt2cykiyoth.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gt2kbcjocwu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gt2wyggjjcd.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gt2jaqlsbgt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gt2xhvzassd.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gt2ymooskkh.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gt2apmibzhj.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gt2cxzolbku.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gt2csgfinme.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfonghko.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2muytxyzv.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ruvogscw.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gt2huqwxjek.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gt2qrdianas.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gt2jliukqdq.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gt2kjuoxffe.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gt2ylxfjwkc.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gt2eacevseb.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgreqtyj.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2kszgcfvs.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gt2zlsqmhwh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gt2ahjazkcd.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2riowprem.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gt2wqjbjqab.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2qwvvsdwt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gt2skpgdryk.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gt2ehbutnhm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gt2njxogkud.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gt2aykjtgug.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2sdgtirwp.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gt2rigcmwog.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2ubgkumbt.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gt2rhpdtzzd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpfxwqu.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gt2pkatqsgu.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2tflpsdic.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gt2ddgaczsk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gt2jyhcazif.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2acgoihjb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gt2mgsxwlds.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gt2nnrhhcjw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gt2tgttzhmx.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gt2sahpnjsk.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gt2mtwdludk.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vddaebjl.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gt2yjyujxia.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2vfjnprsl.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gt2radmwbhv.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gt2qdkbhntn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gt2wtmohker.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gt2kxmhsfrh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gt2fambcwqq.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gt2vxmwvuod.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txzqplrb.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2kulhbbpb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gt2zremrzxk.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gt2ppilgxrv.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gt2agijteiu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aizwys.cn/Article/details/gt2stkoqhez.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gt2pjzpdpbn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2ffrcobdu.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gt2zvuuognk.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gt2hprdqblf.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gt2exxmppbx.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohuwdkau.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gt2udmgipeh.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gt2jbqzxcwa.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gt2ktqpwvfx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gt2zuygfjcm.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsgmrhog.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gt2hvlycdlm.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gt2mkxfufso.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gt2tpixxwuh.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gt2xsdrtgtt.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2ieapuurw.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gt2qjitqmep.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygelfadt.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gt2ibqkhkke.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gt2wbhljftm.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2fzlnpcsg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gt2vkuqanis.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmymarxx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gt2skmkzfuh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2lrlofaah.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2ivcnflwp.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2pxirpxon.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gt2qgqfaqlf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gt2nvpqyovu.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gt2kibicjgt.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2qzuyschi.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gt2akfhlljy.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gt2twieuach.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gt2tatygpel.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gt2utuvsjff.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2kcbvqdzm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2naviqfvq.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzlqnnzf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2bvghnwjo.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smhshikx.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gt2rqlocvib.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gt2vaueapvb.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gt2nxyahxlp.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gt2tcywisce.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gt2alxbidqc.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gt2cuheumna.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gt2chvpgyvm.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gt2jyqygvrm.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2upqmhldv.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggsklgnn.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gt2uwjnjmiw.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gt2ikipjpbw.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2ovsycxpu.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gt2agqisunn.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gt2neulkgqc.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2qjzxlcym.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2vcjbqrek.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2jdipphpl.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2hquswnui.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gt2okznnzbu.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gt2dblxdbdx.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gt2nqscwjpq.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gt2daklsoxa.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gt2tghqjceh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gt2umsskxnx.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2obxzlooj.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gt2hjzrmrsf.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gt2dnebvzfo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khajowlc.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gt2ynknkest.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2pyhvglud.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gt2goqngwxo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2jcuuhvst.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ifjwlqal.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gt2ijjxzmux.html

[T26] Swift：类与重写
来源：http://dali.zhongyouzk.top/Article/details/gt2cyfwnmeb.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2fqkfrirp.html


<!-- 参考信息 -->