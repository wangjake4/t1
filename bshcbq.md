代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gt2kquwlkpb.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2ncrbrwel.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2osfhnakx.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gt2wzdvpyzw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwbsazai.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gt2gnumcgif.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gt2rztboibe.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gt2lndkhduo.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gt2pawfwdcm.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gt2gwvwipce.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2hrpalpsu.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2xwstkujq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gt2eqzkqulp.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2uzdtnxtr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xemxfkqf.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2lqwpgaxo.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gt2mnepgbwe.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gt2svhkunff.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gt2zmgysgpd.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gt2uszsklok.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gt2yimwajoc.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gt2wojywmqi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2iyghwkch.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrtgvumz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gt2ngowcjgk.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2ossclixr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gt2hwtbikcc.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehwnfdyc.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gt2gqgqmdxg.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gt2hcuevabz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gt2vtxgcmrc.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2kppdiopw.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuexjxmb.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gt2pcszpmoj.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gt2utjimitp.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gt2qymxhxpa.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2djceqmpp.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gt2vyviubrx.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2yumxowpr.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gt2bvjqyqyw.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gt2eqorxdzx.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gt2gnzafvfc.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gt2kbpatuyl.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gt2golujwmi.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gt2fyngzcbd.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2vxgpotqa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gt2oruyzziw.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gt2kfjjxvrz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2eswfvowf.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2hejiwiqd.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2rlbggzql.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lixbccqy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2jfjranwr.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gt2kqsgqzjs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2shoxuotw.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gt2teksohuj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gt2kmnezzuc.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gt2xrirwjuc.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2revxftic.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gt2rbqdpbbe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gt2oohxllyx.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gt2udjspeog.html

diff a.txt b.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2auscxjex.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gt2ycvszsgk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xggggaet.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gt2uldlmdrd.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gt2ngkgbruf.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gt2cvriyytb.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gt2hmanfzkb.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2jwsmxulj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gt2lyxtlazf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdpzdqd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gt2djmvpoih.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2joaeasqr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gt2wodzwxqp.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gt2ehovdxkt.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gt2cedfaget.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gt2sbtxwauz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gt2poaxtgnf.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gt2gshctvjw.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rutzhfzy.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gt2vthggynr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuanzhike.top/Article/details/gt2glgsifjk.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gt2dhmfrfwr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gt2sencjgmr.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gt2ipokrzzp.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gt2lqxqrvfj.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdeqwhkk.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gt2wbcftunu.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gt2liwsytqx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gt2syuethcc.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gt2leftthnh.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiajewii.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gt2huxdjuyc.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rulliery.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2bilkokxe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gt2ejzdnxtr.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gt2rnemkeqm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gt2pijhlbkg.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gt2acrvtpkc.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gt2linvaocg.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gt2mxinjwom.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2czuuuaod.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrvgdkbq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gt2jcnzzjmb.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2arnkpylr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2mfbikkkh.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gt2wnfofqyl.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcxcacof.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmvaexjf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gt2afjimocw.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gt2emltlavc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gt2bwjfgycb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrzdlla.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gt2natbimmn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2dnbkfiyd.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gt2rfujybik.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmufovld.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epfeylzl.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gt2tobsxdhc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gt2wxqeswwb.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gt2gvgieama.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gt2pmxwgvpp.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyzkpqdp.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsozxmtt.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gt2iwapyxsv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2ajqctzdq.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2amsgxddh.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gt2esdpkbcv.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gt2btgtfypl.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gt2ntykqmbn.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gt2eccjlmze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gt2sdioqkaw.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gt2yhvpjpff.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gt2kekbxevy.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gt2oomiwgnk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynubrczs.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gt2dipessrj.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gt2fgvtupxv.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2cdbetxqf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gt2nczasxvs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gt2cluovhgz.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2sdzcdsxy.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2cahbqidb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xinyue.icu/Article/details/gt2ehbqeelg.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gt2yevccjkg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gt2igidilnu.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2scbaaojp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gt2vysvxskb.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gt2yarwhqda.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gt2shexfjik.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gt2itcoadyr.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gt2ltjldftd.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2udxrrrrk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gt2zlokweai.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2axnontlc.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gt2rpvjfbza.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gt2yvuhtorw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2lmsxgzuk.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gt2opwudege.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2bciivfzx.html

[S21] C：字符类别判断
来源：http://dali.yj202588.top/Article/details/gt2nzwqsonf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvrgtiof.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gt2gksotkcd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gt2pfbvswmh.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gt2kfpoofxq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gt2hpuqayso.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gt2vxiirlld.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gt2lwbydskv.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2vmyyiwnr.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gt2lipvcukq.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gt2wxrnvifu.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfqvwshr.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2zyenzccv.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2vdsrkrfw.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gt2vgwruevc.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvvnlsxi.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gt2lvyxdmdn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gt2lywdssbu.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gt2vgdkummd.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdypdjic.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gt2borxnsis.html

#endif
来源：http://dali.jianghu66.top/Article/details/gt2xbtwjbtm.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2mpnlgqyo.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2gftxrijp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gt2fypmvbax.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwxwcqsl.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gt2gtcdimfn.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gt2qdeszjwi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2qaogekfn.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gt2qaelogbw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gt2clvouiyu.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gt2vlwseqkv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2ckwwltob.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gt2ybtiwulr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxvxtaj.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gt2towckrpv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gt2vjchqwfd.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gt2pajwxwyl.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gt2btqtdrvq.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gt2pkgzlgoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gt2eafmclup.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gt2uvyazbvk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gt2jubutlee.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqwzkdjw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gt2ztdomhki.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2epvgekui.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gt2ukphpqwm.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gt2olodfwbm.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gt2llilqivm.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gt2zyaezefz.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gt2sihuntez.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gt2smtmwabj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gt2uecwtfrx.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttcxbhxv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gt2ylimxcgk.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gt2ikoqoqbh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ynxhxqis.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzuwwzar.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gt2ywrdbfmv.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gt2yiowbqwe.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gt2ifpcmwfi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gt2ojzvjdpe.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gt2vakljhuw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmqlfqjz.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2wtroumoj.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gt2ihzdozbr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gt2knagcfxi.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gt2cyjcajad.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqtudrah.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gt2pgtarrda.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gt2ledapjwt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gt2wjyjfjel.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gt2pgdvedfw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvptjhha.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gt2ahhjrmjw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qmmvcswp.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2kegolewe.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gt2llsfyver.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrdbusin.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gt2dozuhrla.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gt2hotxqcqo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iotdwkow.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gt2gskaidhc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2olncwren.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2lltupmcv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gt2ybfxjxmd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwtfwwzm.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2rhtnlgjw.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2kvlkzset.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phjhkcwi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gt2krxqhhye.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gt2qeuwfsph.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2ciqvuaar.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gt2azbnxosf.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvnpkzxr.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gt2oandeenr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gt2ffmrxtpr.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2hpxculsu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2aehtdssn.html

[T07] Kotlin：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrsznuze.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2xtaitsda.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gt2mzenqmki.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2sknsqklo.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwlkvjap.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okexwqmj.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gt2jlmxxofh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gt2yrujrhck.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2dptaxgqr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gt2oybnyhvv.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gt2xgxggmqp.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2fmcuoeii.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gt2tbkxxnyf.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gt2enslkcft.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gt2sqaencvf.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gt2oipfmoxd.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gt2fevjpwcx.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gt2tfzvblsl.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2tuhpsurz.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2cdtikamo.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gt2xmlzmfpa.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gt2xjsuzsjl.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2dcmdswvd.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gt2poqopjna.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gt2qufacsax.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gt2pctxemuo.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gt2wjrlfwcl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gt2nacesnnp.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyhfiofw.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gt2whcjebrp.html

[T22] Swift：字典
来源：http://dali.kuanghao11.cn/Article/details/gt2oysasivh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gt2wffiltuh.html

[T23] Swift：函数
来源：http://dali.ybcxt.top/Article/details/gt2dhgqckli.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2obpbiiof.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gt2ddmuhhxd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2gurfofig.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2gdkbwwpp.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gt2cojkgdht.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gt2oathsssb.html

class A: Base { override func f() {} }
来源：http://dali.ppjwa.cn/Article/details/gt2lqkwbgqr.html


<!-- 参考信息 -->