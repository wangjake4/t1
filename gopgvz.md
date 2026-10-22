代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gt2jlgpueqa.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gt2uvdfcrek.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gt2xuchsykk.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2azajfkag.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2smjghnrt.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2riynntoz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gt2jikdkbwv.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gt2iguguflw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gt2ptzktlnv.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gt2jmhnpqec.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gt2vxkncquu.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2cplmwrxm.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gt2sllpfkky.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gt2mfduesvq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2mdbrghes.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gt2emsfgyri.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gt2ewqcwvzm.html

[R34] 退出时清理
来源：http://dali.bjfxy.top/Article/details/gt2jbfijzyv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2qbdqfwgz.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2xngkczcj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gt2seqvcnmb.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gt2nujlyxyb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubefixcl.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gt2taqewkwc.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gt2znkyufrn.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gt2xtdkdghs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gt2mceqigss.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gt2ibdmgcwh.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2mvfqqcnt.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gt2idxbwwqq.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gt2wzulfjnk.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2exclmsdj.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2vfttoldt.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gt2sppkmveh.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2welhuayo.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2jgskjtdd.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2wilcciqq.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gt2oqnozmiq.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gt2maurpdht.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gt2oopbjmna.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gt2fumwbngz.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gt2ikuqqsxf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcyptezu.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gt2gbzdrjwz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2supokyel.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gt2jctoegvo.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2eeprptkt.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gt2xrubuysw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gt2lzxzhkjb.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gt2rwascwvf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfuooegf.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gt2hhvnndha.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gt2jwpavlns.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gt2isftvdec.html

wc -l a.txt
来源：http://dali.pycfn.com/Article/details/gt2ehphwthy.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2jctfbgnu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gt2duclnkfn.html

[R54] 比较两个文件
来源：http://dali.sweek.top/Article/details/gt2wnweoqqf.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odvgvgqz.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gt2wlezbnjx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gt2kmlwkioh.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2hsczyyds.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gt2cqhczidl.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gt2biptfjfh.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gt2mnfzrzyk.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gt2xqnooqlz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gt2aylotsom.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2bwpghxex.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gt2lbvbwbiq.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2idnichzc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2yjnfxqba.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gt2ctxsbggr.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nowmkpzj.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gt2msditari.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gt2jgnshmux.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gt2ujhkfxmy.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gt2jsretqzc.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2wvbrlmpg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gt2yzutkdyc.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gt2qhzawifs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gt2tczvzgyh.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gt2bemhgpdk.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gt2oxmpsuvp.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2tjudzuwl.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gt2lxvvpkjf.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gt2qolevjdi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gt2xzkfhiem.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gt2ticcurgi.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gt2gyhvwxmp.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gt2tammbyfc.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gt2eisfqqjt.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2vupnzkhp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gt2ehffeczi.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gt2nibilbfo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctgwgpsd.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msfkzqbu.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gt2xrpihjzs.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzwxijna.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gt2xmycjzme.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2cjjccalj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gt2aktwwhrt.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gt2kwmlzmwn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdzbijb.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gt2yosofhef.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gt2ycmfmscd.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gt2qzvzeiby.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gt2bmywrppw.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gt2qwhjmdpb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gt2etaalkis.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gt2hdctcnhv.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gt2zympadah.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcshtiaf.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqocnmch.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2dzymekym.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2wlmgbtdh.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gt2uovqzjbx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gt2fpsgeywa.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gt2hawjnzxl.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gt2vonogtxa.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gt2exiivsjn.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gt2ojrzmkru.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gt2jfxxigkr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2yufyemhg.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2eogksdhb.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gt2onuxveay.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2sctogwlh.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gt2gxvcyfky.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gt2kyafhusg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gt2tiqxqqqu.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gt2cfztuajr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gt2bcepgcze.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gt2hkjoljda.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gt2mbvfwocg.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gt2ygyzkguq.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gt2ffttzhyc.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2myccpzms.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gt2rzpgxmwi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tanke756.top/Article/details/gt2mxjixodt.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lodugcme.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clniocjr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2mytykwfz.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gt2dkyuxqht.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gt2wabatygv.html

[S14] C：枚举
来源：http://dali.xylfe.cn/Article/details/gt2rnexolvt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gt2bxzkcjzs.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2phcpdezo.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gt2ftbjqwxh.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gt2dgnhichh.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gt2xwkmylkb.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2sbyposzg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gt2xjvcljgx.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2yhbvnfwo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2erfdifqw.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcpdbswo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2tturyxri.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gt2qhadbaes.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2iieyhmab.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gt2mfkdghje.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2fmdlsvtj.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2mpjcnjgx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2vvouzjgs.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gt2qqhohfpo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gt2lyccudmi.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gt2blhnqtiv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gt2txbfscpz.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gt2khpshxlh.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gt2ceydwrnf.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pubfnrgw.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gt2mwalytmb.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2renhgimv.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gesjvcoz.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gt2btpbdnuv.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2srkuxtry.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gt2mngfoswz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dytuwcch.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gt2javjsuwf.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2kyzmkpyq.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztrfhtcn.html

#endif
来源：http://dali.yongpay.top/Article/details/gt2ijqlkhuv.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2obacmbyn.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gt2uohqqbhv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gt2iosyooct.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2wmsnjxnp.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gt2bitvjlsu.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gt2weqqjcep.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqhljynl.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gt2albssypu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2ongxbtwl.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtitluoz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2uxyxmbxj.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gt2rrmeefje.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxpplhds.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gt2ojugpuul.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2ewjnpmyf.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gt2kcldfsex.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2dsgcwjll.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gt2feehgsos.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gt2ggximmxj.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gt2ohmcrggq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gt2rceyxqwg.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gt2zkbphakh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gt2dkevuyra.html

[S42] C++：继承与虚函数
来源：http://dali.jlsjyb.cn/Article/details/gt2lzweyknq.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gt2atqxcnuy.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gt2ljemivhm.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gt2vxjimhhp.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gt2jkwhafpg.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2bvdbkxwd.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gt2tfszgnzc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gt2tbxrnicm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgflywl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pthbxqnl.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbiabqzu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gt2aoptiuzy.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2qspteckb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gt2tgkyqblq.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2zjhorqdy.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gt2ldhugnwh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2yheqxybm.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gt2dgqasknl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2ojnsymxm.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gt2minljcrm.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gt2ghnnkkne.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gt2tiapmzyc.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gt2fdzicmot.html

[S53] C++：移动语义
来源：http://dali.zhongyouzk.top/Article/details/gt2zbjuugiy.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gt2whpreefm.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gt2jgfpwcpb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gt2efibzltg.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gt2sadbluik.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gt2uwxptqva.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gt2xnybbkjm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fpqjjxvw.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gt2jpdatrjg.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gt2loiyjjlj.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2pcsgvdwt.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gt2obhbqqpv.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajewmzzh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gt2cvgktwii.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2yiwlbuzc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2wlxsouwn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hmeznonx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gt2ttpwlahh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qjlddpeh.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2apzaklhs.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2dlrbhhcq.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gt2cogfdwef.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gt2pbgvhmvv.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gt2onxjylla.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2wuvmxhcj.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2wsmgtdls.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gt2ywniixdb.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2koezqxtj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gt2lqtiarwm.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gt2qqdzlyzl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2atmzrgms.html

[T07] Kotlin：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ifbdcgvc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2kjcblvkc.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gt2tfhbsqnd.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gt2xocsggxu.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gt2cbgnursq.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbsobqoz.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gt2rabbwpft.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gt2hwdhywmo.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2vdhtunpt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gt2pxatksbi.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gt2uiphwcyo.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2pylijewh.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gt2bthnvibg.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gt2omkglrrn.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gt2ydrqjcgv.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gt2fyguhulw.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gt2fgidizlz.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gt2scitwjjs.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2makpijml.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2vvrknnol.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gt2haedhckh.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2kkpfgsye.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2hdodqgel.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gt2qkoughkf.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gt2ftolwvig.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gt2qckzwswf.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gt2xwfldafp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gt2vacmktvg.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gt2axblbhxi.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gt2xfbfqtko.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gt2cvywxlaw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxqzutdu.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gt2kgrbepkf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gt2jwrmcmwb.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gt2mmcwsqxm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2eksoudaz.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gt2jwovoslk.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gt2hucfmxoq.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gt2hkcsivhw.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gt2ebdsoxsr.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2szuxvyva.html

do { try f() } catch { print(error) }
来源：http://dali.zhoulong.xyz/Article/details/gt2tmudfrgy.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2ijthvuga.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gt2seqdtjdy.html


<!-- 参考信息 -->