代发 wailian999

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gtduxznpqw.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtzoukndas.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gtjbktrmps.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gttjxdidwq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gtbthrsenw.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtanfujzup.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtsmmrswcz.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtfpxmupwx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtljxybuoy.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrtusjer.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtwgjmpuld.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gtqgtzqfdx.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtwndswooc.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gtdbrzfgut.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtzfpnyedy.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtiygncrsr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxuanxn.top/Article/details/gtothvpavp.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gtubifwhsw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtxszpudyx.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtmiywvmbn.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gtouockkqh.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtfomnazia.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtetjjgbzm.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gticzqqqcj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtljhbagtd.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtrweuymcl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtowfhuvfp.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtbrsixnlp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgqthazv.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtrmblular.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtmhrrfszz.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtvegeoxxs.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gtxpbgdpke.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gtkoqamdyc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gtueirwpmf.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtmknmwdhz.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtszlaxjsn.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gtaugbegws.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtbjaqqnis.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gtqxuqubeo.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtvalhozdr.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtiruqekho.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtutksnhgc.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gtrtyzvpfx.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtouuxqxzn.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtlsirjbyd.html

find . -mtime -7 -type f
来源：http://dali.jinqigfzy.top/Article/details/gtbnaordrz.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtqnzrsvuk.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtrqrtajtj.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtqkjfbfhg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtffoihhwl.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkgrrvzw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtsfzcbypz.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gtkzxvwctb.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gtzxdeyqvw.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeacmidf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtpotefdhj.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmsqqpyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gttjudmnii.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtufhvidvj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtzbujrcrs.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gtdiplbyyu.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gtwismgnai.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtcngwgpuy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gtlmigvbrp.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gtdkuyqvdj.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gteybiuumk.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtmgusqcqo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gtuwpmnivt.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtspjfcayl.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtfjhrqrjz.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtzzlxggpw.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtznizmrfc.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gtgiskzarw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtpqqelqzi.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtgqntuqqj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtfggyjdmm.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gttpgndlsy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gttazlckcy.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtayhpramv.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gtuptunqjb.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtvcbqeltj.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtolrefmaj.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtktycesdo.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gtdddvdxar.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtepaeosdi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gthkoxswcz.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtcuheachd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtylwvwjcj.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtrxtqszfd.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gtvypjbgbt.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtazoofyod.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtyiwpizrt.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gttpzzgmia.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtvabmulwf.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtjzarxdae.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtkbxgcuso.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gthobzrwcz.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgftragza.html

[R71] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtbuwcabvp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gtyjsfjjyo.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtudcvfgiq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtgpvskaqu.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtpmygnqqx.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtbmdvexay.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtyhproant.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtxlephzej.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtateuvwno.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gtyrtryjbt.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gthsjcqdla.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtgilngpwd.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgeptyjv.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gtekecqtgv.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gtijmwvzfx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gtqtdopucd.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtcunoprlm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtbbomlcpx.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtssycccpm.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gtuxinejxj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqcspbjvr.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtofragdet.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbrpbuuwb.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtnenrseov.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gtklgohayr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtwbtflmcx.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtyzvbaecr.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangshuangyany.cn/Article/details/gthhwroujy.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gtetcjjvnb.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtsblcnqbv.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmqrttnc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gtasfxmggm.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtjsqvciyi.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtnkhtiony.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtslwpjnbx.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtbmqipefs.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtjqbrdojl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtropikzdt.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtubpgyeym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gtyopjuafm.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtigjswqch.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtexmdvfto.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gttesmntlx.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gtbomcwkiy.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gttxzottwm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtvjjypisl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtmykhfmbp.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtqwihfxkn.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtmrdzeyys.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gteaxpcihn.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtnaknvsvo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtmfvjczeo.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtnzorvmbt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtewkhpxxo.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtjgzmtbbc.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtvpaugoaa.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzrybuho.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gteqmxqldb.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtxcsdunjn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gtknzkjova.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gtvedvaxoe.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gteldevjmz.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtzxvdxmjb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtyjzjqgqx.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gtbsgfxxdy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtqfwjkync.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gtssrfkzaf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtjcjezbmz.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtthhuxjko.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtybsdmrcc.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gtmblgdkiy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtjhttxaja.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtxfatrtud.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jiagoushi.top/Article/details/gtrknkwhev.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gtvkerityh.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gttvzstyws.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjovtfnsa.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtezturqmu.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtaqkgyvbm.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwhojofr.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtxipofmxs.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtnkjsjqtt.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtlaiuwmul.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtdkdicfqo.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtdsqucpdb.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtculogywb.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtgyaieijv.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtvkufzcat.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gtkupcramv.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtzfjbbnva.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gtxleukast.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gtbyfxunok.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtpulaftnd.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gtfocaaaxn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gtqgkyvgwt.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmupohftx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gttltdqrow.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtqxzntyvn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtiuxpceke.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtnskmbujg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtflkzjhig.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtklgxgiey.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtuaudvkeq.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtbvnmzuio.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtpeolhxrb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtssbvmvsr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtbnmqylsc.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtnmwrzgag.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtavkjkthr.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtqubdpxet.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gtegvrreph.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gthzwnjyxz.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtsbzsdwjo.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gtkpmzpaon.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtudyyspuo.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtmvmvslyb.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gtmjcreirv.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtveckhxxq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gtxoswmzmg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtohimrclj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gtwsuqnmck.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdivozel.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtctcdvchy.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gttthkngbm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtmvwuieml.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtsmvoiilj.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gtbsozdffm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtnskyyfmp.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gtsmglcwut.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtdjgmhztl.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gtfddajvgi.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gtpwqbkytz.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gtefeyrjrd.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gturzrzcht.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtmognipky.html

std::vector<int> w = std::move(v);
来源：http://dali.zhixingplan.top/Article/details/gtbtzwrlsu.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gtxnhqsucp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtbqplcgza.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtrbtxuqch.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtgxcbdzrz.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gtfahkuzlr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gtqdmkvmam.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gthzalybsq.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtqlmrwumf.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtbpotazlw.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtxespvmhg.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtliqqqgac.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtudmpsxqq.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gtundzidrz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtkeamhuas.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvubwuzno.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtbpiopkak.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwlozadfh.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtjnumozid.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtjxhaznpt.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtsrneqatk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gtsjcisccb.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gtshnqdreh.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtzbdvxdxd.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gtptpefhtd.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gtyrrmxqka.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gtimfqtrub.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtcamytlrr.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtnaubkvzx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtytxdhinq.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtkasjifmu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtuepfgwod.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtatuzffia.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtbncncnvw.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gtvjrgdhie.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtdscdyebv.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtqjtkqwfl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gtjnqxbagm.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gthkkofpay.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtxgwqekpx.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtueppttlw.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gtrdfwreca.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gtfnvttrlv.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gttpfxgtxq.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtelpqqrfq.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtatoicywn.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gtmubscvyp.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtaxghglwa.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtoyyvjagp.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtrubksipj.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnbnajhc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtlcnbahxh.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtxvievbii.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtfwaxdzxj.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtfgamsofg.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtzwcecdtj.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gtzdaxudaj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gtynubzmrj.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gtlmnsrvag.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtphajjfun.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gthbcdowdl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtbqiounrv.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtioidvfkj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gtoljienwh.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgjukirb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtpkxiexvb.html


<!-- 参考信息 -->