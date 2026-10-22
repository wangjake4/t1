代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2kedgdxqe.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2argheuug.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gt2lykhrqht.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gt2pcrmydgm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gt2wsdgjewy.html

[R26] 命令替换
来源：http://dali.jyoumei.cn/Article/details/gt2wlywynkd.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gt2nchwiyrg.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gt2ubjdvzml.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gt2bwhdldgv.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gt2uayvwgrt.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gt2zasqmnvw.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gt2qghzjgea.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gt2ywyrinhq.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gt2xzidxkfe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gt2tdwwbhux.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2pffvlhnj.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gt2ysdiidms.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gt2nmdpcyhx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puzmtnqm.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gt2oqnzohxz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gt2breoazvr.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gt2hiuxavud.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gt2smyphdgt.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gt2heehjdid.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gt2xuyvoetv.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gt2rmdjyuzb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2hymehocl.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gt2ukfbvuky.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2spehvjox.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gt2nfadidil.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gt2zfueryqa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gt2efxngyhx.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2nphhsntx.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gt2ubhpexrs.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gt2cchyvhki.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gt2lhtbqdxz.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujbrgwfz.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2pidkrbzi.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2ouwwozrg.html

[R43] 按名字查找文件
来源：http://dali.svipenyu.cn/Article/details/gt2tzoyaqat.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gt2wjlfhsdi.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gt2ockujhor.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gt2wcuvbatf.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gt2lidmzbrr.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gt2cbgkmcyj.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gt2gyhfyuhb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gt2eapfdjed.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gt2fsinbrzf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2syokinoq.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gt2txuijauq.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2pqbzysbr.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gt2lpwflwvb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gt2kywxmmji.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gt2iykwbepb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjpsrua.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gt2lvjwgvkj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gt2clibeptq.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcrfhjcq.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2ahtfwhqr.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gt2xvsldtqy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hammf.cn/Article/details/gt2bvmswldh.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gt2uqtbjyzu.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sspqxptt.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gt2zqlcejwx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atzpgwcb.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2txpgvigw.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gt2usviyehi.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gt2sghyezgz.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gt2ysqhttup.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2ftpzrmxx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gt2dmcqrysm.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2hegvlkql.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gt2lortlory.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2ntqlagiv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2pwrusamf.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gt2tgahzbwm.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gt2prohtleg.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsglppvi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzxeybea.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gt2nuptpdxi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsphvph.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gt2xclhufgi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gt2yoknqpss.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2ieacoysz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gt2mmipeocy.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gt2aeafyzst.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gt2pfcwotqd.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gt2fqqtekal.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gt2pvzvhymy.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gt2fgparriy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2uvkkdhis.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gt2iuoxzssk.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gt2afmiuolw.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gt2xuqxfyxc.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gt2hgmgxxpi.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2wkgevtpc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyrwjjur.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gt2rvdzldnq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gt2ddhogkel.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gt2tosyijcz.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gt2ibeddhga.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkncrqlt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fzhhl.top/Article/details/gt2bgvibfku.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gt2mcxujsha.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gt2rkyqhxzi.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2vjguwpsm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gt2ptjejtrg.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gt2qvkwntiq.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gt2hykjiyob.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gt2iyprwtla.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gt2jisvwvwz.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnlepfqb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gt2lieulgug.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gt2nejhpubl.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gt2aoumaouf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2rivfhtit.html

S. C / C++ 专题
来源：http://dali.yongpay.top/Article/details/gt2elpybred.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dsprwvrw.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2apbtyxhx.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gt2aayygnux.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gt2pgseddzq.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gt2stawwcox.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gt2rrvyndak.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gt2pncnfgfq.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdzlmwvo.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoqdznbc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2mjxbhsgt.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gt2yumdgqii.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gt2rhjpcomj.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2zycwdllf.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2azsipote.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gt2lfpkwayq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2pgobetxs.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gt2talhmgzu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2obgoellp.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gt2bmbucigp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gt2pyvvlhkn.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gt2yqjdkijb.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gt2fsjajrxk.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2cfvahjqj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwbgoqhb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gt2ajxneyxr.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2affnmuon.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2wgympngr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2asnjzyvo.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gt2chzaiasb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gt2jrjnskwp.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2tqtmipej.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gt2inuqvdgi.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slscwolr.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnucfldm.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gt2odhejsqj.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gt2tvqcrbmd.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2gwiegjyn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gt2ombgfuek.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2rkswdmwp.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gt2qhvxfmdv.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gt2uorjjnur.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2mkbctrto.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gt2deevznkc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2bwbotzov.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gt2ztwzsijo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvjzwhze.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gt2euttvedd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2pquabsul.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gt2nqzvnwvr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gt2aquiajwi.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gt2hhitaxtp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gt2cvnhjeer.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gt2iwwjewks.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gt2qxzxfavd.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gt2dlkuemmi.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gt2hqmkjvvg.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gt2zxeflsbm.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2zrwknyue.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2htrzredt.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gt2cicxavhn.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gt2zziwlcyg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gt2vwzvvgwb.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gt2flqxtyen.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gt2ioqlxzep.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2cofycejo.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2esnmfghp.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2kcsyvtvw.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrrijywi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gt2hdysewte.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2gbbgafcq.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gt2xctqwqwv.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2ebwftrej.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gt2iojwwdxa.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gt2ireibndg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gt2forjdhbo.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfrsnlco.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2wdppoowd.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gt2jhxmnazh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2wsqlvbwt.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gt2zykltxuh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gt2rfviletj.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bblrqqrj.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gt2dnittggt.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gt2ejrnwbvz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2avgngafu.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gt2lqbdoxhb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2mkrnvymv.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gt2xyonjckg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gt2mrbalzuh.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gt2qyvsbfyp.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gt2dllldzdf.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gt2yrkvkbri.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gt2xvkptoro.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gt2kcidbahy.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gt2jxhyqpmm.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftisoqew.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gt2qartjngn.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gt2pqunubvm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gt2ahooxqlq.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2blucndjy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2bbzygnlg.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2fnwqbdap.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2pfyzdmni.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gt2lajmowpt.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gt2voprkrpo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdoagwhi.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gt2thkyasdw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2wxjwjaiu.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gt2boysacab.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gt2rqehguao.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2epljmhga.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gt2nnmyizlr.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gt2cpxkzmnf.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gt2nogskurx.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gt2lcrvatws.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvcknjej.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gt2npzzpapx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gt2ofdxgquw.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gt2ofksmzru.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ppjwa.cn/Article/details/gt2besbpudo.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gt2bsvacvqv.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gt2kbhvxwzm.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gt2fywjqvma.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gt2rcvdizmq.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gt2ssiauhxf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gt2lwoqfxia.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gt2voqrcucq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2gejkhors.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2gqqijhcv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gt2pqcerfth.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2lezuskvy.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2kfscpbim.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2bjbnmbhc.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gt2gyditbtg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gt2rkfmdpeh.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gt2cirjitly.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gt2xfwjdbih.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gt2xwqjgjlk.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gt2hqozvohw.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gt2omgdtpco.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gt2xcpcludk.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2wotymscg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2nhanuawv.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gt2gufxfxku.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gt2qetahwbz.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gt2sjuucxcw.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gt2bsuwdqzb.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gt2shzeojbt.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gt2izjsaydt.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gt2gijaltpr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gt2phstersx.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2hfafvqss.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gt2ditjfzic.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcczsvgx.html

val (a, b) = Pair(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2mkzrlngo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2hlpafvrc.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gt2hjhjcwwk.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gt2xwujaqxw.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gt2lfvndhel.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gt2zddvnjzc.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gt2ccndgrtv.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gt2ozeitadw.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2ajgqkbgv.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gt2fmlbuiyb.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gt2ksbrhzmh.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjqecpxz.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gt2yyryvutn.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gt2ucibmfnx.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gt2zgufzwba.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gt2vngjbojt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gt2weyhwdok.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxjnfvxy.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gt2eupeklky.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gt2vgtiadal.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gt2ksllexog.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2vedcmsho.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gt2qsxjgmho.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gt2yodsanuw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2rjehfhhz.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gt2igadclyy.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gt2omobepub.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gt2ehttotbi.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gt2djoxqtak.html


<!-- 参考信息 -->