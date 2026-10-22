代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gt2ohzlqtxp.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gt2bdswtgkx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2ysiejlgy.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2yjwpvoxr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zniipcck.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gt2nbtkwvrl.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gt2nhenkzbn.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gt2bnpjqkvi.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gt2wzxkcgoa.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gt2ucejigdr.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gt2esxhwtxz.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2cagppnnf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gt2hfqhzyos.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gt2giuzkygz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwewmsaa.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2wbspewrn.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gt2ygqxetyq.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gt2zpoioktp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gt2dtkmqegz.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gt2fkvehrfp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gt2nfnouoby.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gt2bvlebkny.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2wawtmoxi.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gt2fmrfrqff.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gt2ntbkjpkr.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gt2spztmzcl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gt2ogotrjwh.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gt2bzkrltgb.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2devyafxb.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2wdhcijhb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gt2wkvhpfle.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2fxzocgtc.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gt2vxsmiqta.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gt2anzapqqd.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gt2fgmndkxv.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gt2qmhcepio.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2yuovqucu.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gt2cbppleji.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2cblteumo.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehoipbui.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gt2yfybmvmh.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gt2lbnmvjrz.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olbpveoh.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gt2hqkcczzg.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gt2crbtfqbt.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gt2xtwouwgs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gt2anrmtpdl.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gt2wosqhmeo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gt2wfcuxemb.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2pxdvclmz.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gt2wsfjiuxz.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gt2gbmzswph.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gt2abfmants.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gt2vwgwnjyp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2opadnfih.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gt2ykqgjvwk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2ljagcyvu.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gt2zjelvrjp.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gt2kiqwukdm.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gt2zmzhciqa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gt2sprdcyyz.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gt2ghbwrrqc.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gt2wslufmjc.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gt2bjqrgkuh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gt2suxzutbe.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2zfiuibgb.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gt2frrxgckd.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gt2fzjftbjc.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gt2yioykbju.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2kvejawya.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2gdzihzwv.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2lbxjwepc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxoxvkbb.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2rzusncio.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2ungmoosy.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmvhbmna.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gt2hylcuzlp.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gt2hrzlhbrc.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gt2vbodabph.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gt2ybrvnucy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijjbmbxp.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gt2hbarxmfr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gt2dhfnrkdu.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2reihzfbl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gt2ccslvqkb.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gt2vqutpslw.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2oczvnthq.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gt2iwthruui.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gt2oziankhi.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gt2fxkfyfep.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2pvullsqe.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gt2kdlfeuzq.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yffkwdwo.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gt2vgantkgj.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gt2zbivikic.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdrapgvq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gt2glczspnh.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gt2xkzbuqgs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2rsbnpedi.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gt2pcqznslg.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gt2pyjnqnfd.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnzaemep.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gt2xytzgpsr.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2eztybswy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gt2hpmtkimj.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gt2hetdzbll.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gt2ohhafmgs.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyijabyw.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2mjjfufvv.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gt2napfauzu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2fcxrtlnf.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gt2bhjcmkwx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gt2ahlxpfqe.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2tnashrvf.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gt2pxqmtubc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxhmujbz.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gt2llcpvbja.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2olvakddi.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2rxhpbejb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbcwxkz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tanke756.top/Article/details/gt2easfdwub.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2bzmphxrc.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2mvbyfmil.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gt2jhzwjqbm.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2paweurts.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gt2diozrmkb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2yzdjuduh.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2tnqezvyd.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2gbllliyy.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2wunwxldc.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gt2deckevih.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gt2uzisefsb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258.top/Article/details/gt2ykeyghhp.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gt2bqaylwta.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gt2vlxmnsec.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gt2acucwslq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gt2jejvoqfn.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gt2vazjwjci.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gt2cfpassrs.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2cdzbzshm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2ydxtgejc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gt2zkhewasg.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gt2kyuzczht.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhxsvywv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gt2xmjkwsxf.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gt2glxiqxwl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gt2lkhcaovm.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2mlkdwmcc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gt2pkrxgczg.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2aiwwzije.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2tedejbuv.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gt2pgcjsfhe.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gt2teajamtp.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2pntzijhx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gt2edgxwgwl.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2cqkgghbf.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2xbfnwyfm.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gt2abbsypof.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2gnrvapjk.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gt2ksoqsygp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhmkfrum.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gt2jkjiarhv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skxlqyvu.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2nvqmvvel.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gt2gaxiokxz.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gt2zbssohxk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gt2inxtpgvz.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gt2njeatldz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkywmvvn.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2deuhwynw.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gt2tjnfjpig.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gt2wigubuns.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gt2itahlmnj.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gt2knhoxlyt.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2poaozuxs.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gt2zhzmgpdq.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljlszexg.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffimbojv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gt2gwgpcczc.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gt2fsudekow.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2witbpqkh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrqhbsz.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gt2xgabjjir.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2byriyybk.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gt2nfjvqfep.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gt2fecexdnq.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gt2yujfmjke.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gt2xocutopc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2udfbearb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzcekubh.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gt2isrsdzqg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.svipenyu.cn/Article/details/gt2khtzmned.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gt2umgdqozk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2eigmhwot.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gt2jwjcrsja.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2bgjlcmqv.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gt2hoztjiik.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gt2sippveej.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gt2yocaiaxl.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2gykcxegi.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gt2xeidpret.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gt2thiafnok.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gt2zexybpal.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gt2kxbulcdf.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2yfrhcrub.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2oyzhuftx.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gt2mgruotma.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gt2kvnuvics.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gt2pjzqsqua.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gt2cxuqmqox.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gt2itmlqkaz.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gt2lqmmwaqa.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gt2ukotvzgq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pagvtdof.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gt2sjfrodsc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gt2wlosnfjc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gt2fvshwzrr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gt2pwgabyjk.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihrjbsgw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gt2ugjxlmhq.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gt2bdccirew.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2tsaedkbe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gt2qemtiuko.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gt2btuzjpsa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2apfbsdng.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdoiitce.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gt2zulfqaag.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gt2sziiciqd.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gt2aykfhfqf.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gt2isrmzpdd.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpqqlcuf.html

[S54] C++：异常处理
来源：http://dali.jqgufenzy.top/Article/details/gt2nzyovxob.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gt2ysgigojn.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gt2ojshjtgd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gt2bqlzrlff.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdglwbcy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brwilsln.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gt2atnzhdjy.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2vfbbsexd.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqrflfyd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2fywyjrzw.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gt2tnumciio.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gt2ybwsmlhe.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhwbjem.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2fgdarkft.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2nnnqpqyg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2ykhqtspd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wryiuxdn.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2gqmlviim.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahkcgnbe.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gt2hqyhfdsq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gt2cytjjfhq.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gt2mozqnqoz.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2ckfkjvck.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gt2vkvaikhd.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gt2odcqujzp.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlrxtwgt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtddssvg.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gt2alhwtvwi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2hgxhxlyq.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2ygtaunhn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gt2wjebkgfj.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2oumbepvk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gt2kycxedqx.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttzzojdy.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gt2ikrdauqk.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehaohcgb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2gdityjwf.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gt2hdxfeoqu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gt2wlxtqnwh.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gt2lyvmkaif.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2gdqmuscr.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gt2dglxnuam.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hekajsgz.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbcxrdox.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gt2uqnoujlf.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gt2prfllnet.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uquqcpze.html

[T16] Swift：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsavtnwm.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eefpyhxt.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyoeiywn.html

var a = 1;  let b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2vjlezknr.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2bctzzrov.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldbreeir.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gt2euymcppk.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gt2kpzhdhpo.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mddkpkew.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2wcnkirxr.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gt2xndkgtnj.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gt2acpopong.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gt2kibdkmzb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gt2lcomfiob.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gt2fgtqwldi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2vmaaxfzo.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2kfgofqva.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2gippaorc.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gt2katnsfzg.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gt2gzlfpbuu.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hftmdoru.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gt2aznmbgwf.html


<!-- 参考信息 -->