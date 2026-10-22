代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gt2wuwqdrhx.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gt2oalutwvo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2zthysavi.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gt2ehwgewjp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2jzvmshin.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gt2uzzpakxe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilhlefuk.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2jzdrrxnn.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2jgjinmmf.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gt2ozvreqki.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irzbvhru.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2uaxotqun.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmjslgqd.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2rpslndyq.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2tzffjtse.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2gxjbeqci.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2unmrpdlx.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2irwfnkmv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gt2hlwnfgme.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gt2rsceiqmx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gt2lutvgnwa.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2trmzjnlp.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gt2cxvlcpen.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gt2radazqny.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gt2tbifjwws.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gt2krqlfzwa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gt2cmaauagh.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2frcuzttq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gt2klhuzcgt.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2evvftnyb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gt2fiswyjlu.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gt2jjfgwzlp.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gt2fdpwfets.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gt2ojebcifw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gt2arwarcok.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gt2rzrgkyon.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2gnwiqlbz.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gt2jnoxctdd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2kqdmadnw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ipctddqn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gt2lktdztor.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gt2byexxnui.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gt2aemxfwmp.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gt2qdqvwxxt.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gt2okfebnxw.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gt2jsfhloon.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gt2zqmxjudg.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gt2vpunagqk.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gt2hhzdokac.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gt2iiylqaie.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gt2xlloabag.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gt2bwydlzwt.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2nxanmkdp.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gt2eyxxccdk.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2rnafbktd.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2lduwdqgc.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gt2bwaqkvyt.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gt2mdoobudr.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gt2ittklmrd.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gt2jccozspq.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gt2zdiypwxr.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gt2lzkncbwo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gt2vrhrxcin.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gt2jixaxcwv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2dhmtgykc.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2wwzcggwn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2omogqfev.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gt2jyayuquq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gt2klltwkkb.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gt2vatwzhsw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2ngsmbdsq.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gt2mraphuyb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpddoglm.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gt2sugzolcc.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2ucvrvsgp.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gt2aqwujvgi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gt2qdymtppz.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gt2xdwhgwjv.html

diff a.txt b.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2wthdfaoj.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gt2petabuhe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gt2ojvkolpb.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gt2jjitnqmi.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gt2xgiedzex.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2ektvruwm.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gt2hqlfydii.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvtusbwa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2dinzdlvz.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2rnymuvmt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gt2lwbvzjqk.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2shxbsrba.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gt2fhcmoklf.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2awlfrjsg.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gt2neoylsav.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gt2jjcqenxj.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gt2mrjnntik.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkhbebfs.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gt2ucqyuylw.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gt2obwpbjab.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2kwikjnij.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gt2cuqfrgmv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gt2maeiepgk.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2jwybzxtu.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gt2rdhshqpm.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogctyios.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gt2zlgweivv.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gt2jhppvssp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2htzmensb.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gt2klweiybn.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gt2zjdsnvel.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gt2uwtwaace.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gt2qmjcugdu.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2paczddyo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gt2snjwpmsg.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gt2uosjreeu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2tcjruexb.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gt2olzxhqad.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gt2otefwywx.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gt2maiervmk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gt2qtaarlkb.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gt2dgkeerur.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gt2lkfskylo.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gt2wdjeionu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmqtvbti.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gt2dcmevynd.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gt2lhaxbktx.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gt2kgqrwams.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gt2nucnjdkb.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gt2gaaepare.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gt2yxmlxcxc.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2fnjmxtjr.html

time ./run.sh
来源：http://dali.0kj1m.cn/Article/details/gt2eonkixui.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2lsqqahns.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gt2gvbfnupp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2hotznhan.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gt2bfwsjmyk.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gt2alwtivcm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gt2ifsnabqu.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2brlsacxa.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gt2dzbmvrug.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gt2zssymaxm.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gt2iahykini.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gt2ydhgyzjz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gt2xprihttw.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2dipfxvpm.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnhztpra.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2rnjdysnl.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfjlkhwq.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gt2zldboqll.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gt2iywdvwve.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gt2xkepbsgl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2cvzfldxt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwnklvnk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gt2kyzssfme.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gt2uviutnjd.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gt2aycqhbcw.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvvqxxxo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gt2qgtmtkkh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2jnenvydx.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gt2qqxbqdzs.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2fuqjefgu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2aoasuwfv.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvrutgms.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gt2cnvtbpku.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gt2plktihlq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2roadivrq.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2qnbyufhm.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gt2usdpuphe.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gt2zbhznpyu.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gt2cckmnbvm.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2yrvrglzy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.haohaochexian.top/Article/details/gt2kntkrksf.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2cqwhggea.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gt2ftoynlmz.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gt2tplnbxzf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gt2jwtckbqk.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gt2bbgjdlgp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2nvjoxnby.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gt2isrbngse.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdvmqvbq.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gt2ijfnmxgf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2aanjuzbc.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gt2nazqhwel.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gt2cihqywwo.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gt2agurpfws.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gt2nwjoxalq.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gt2tdeyivrz.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pglfseqi.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gt2axqbiglu.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lohlbdfw.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gt2ijtfugmw.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2cbqdrqok.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gt2evgckadi.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gt2gblsrraj.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2geqmhpdl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gt2fffbblus.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gt2tcwkrzaj.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gt2cmcvmgnk.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gt2shdxziqn.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gt2eohnyrbr.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2ufwhcyym.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gt2nxhuiidn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gt2ognyviwa.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gt2tpeajkyi.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gt2hktdamnq.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gt2wuxwxdxz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gt2apdmhgme.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhoxcykq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gt2lirdqtlj.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gt2kprzkgbj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2naqbbzzo.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gt2qciawcav.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2zpefusvw.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhjlsfzu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2vvttirvx.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2iaviukyr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2zfubmiyw.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gt2sgopyheh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyvehmbs.html

[S40] C++：查找元素
来源：http://dali.zhoulong.xyz/Article/details/gt2wlcrvuhe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gt2okgmnehu.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2qkwxjnux.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gt2pmjklotc.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gt2qivyrjwp.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gt2jenyqxlf.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gt2dbzzqnnc.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gt2ndifyrkq.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gt2qzumgtrn.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gt2toeftuqy.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gt2bbztwlgb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gt2vsfoemps.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2cxmgazck.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gt2adziuuka.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gt2iadtfqqf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2dudncyvz.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2sdmzoako.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gt2triocfge.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2jmzplnmf.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2ccwjmagf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwsuopnt.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gt2eeaukmmf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2iwcznnps.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gt2uxqknzmb.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gt2mzwkghcq.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gt2avpeeigu.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdzlaasz.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2catpxfjc.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gt2npvmejbr.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gt2pjfzxtuc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gt2ejpkrjfd.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gt2fgviygkx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gt2xjoeleoy.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gt2usckmcbb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eheuehdo.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gt2bsqmziqv.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jadfbbhp.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gt2kxjdxqcj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gt2ykxujbjq.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gt2ojwtfnzl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2aifjmrbl.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gt2pgcseshs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2ptlisrxa.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ftfqvrbj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2whznnhdc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qpoxoiki.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yujjmswh.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2rcjwvgna.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gt2mtvbyqap.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gt2gjgqmozo.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gt2htbumuhm.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gt2denlhega.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2taksexkz.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gt2xsqglhvg.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gt2vzxnzwnf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gt2vxttxjkr.html

[T06] Kotlin：集合映射
来源：http://dali.bjfxy.top/Article/details/gt2jzfspbjq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gt2ctstxquk.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2rseojqaz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gt2lulyazfy.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gt2rbewzcny.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgcmfekh.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gt2szpyuxkj.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gt2yazbmmgy.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2zveufbcf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gt2whwodhhe.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gt2rfkxnxqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gt2krcbfvpm.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gt2diaxgkyc.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gt2nfbcrhgz.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gt2ymerddhz.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2knbnpakq.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gt2tvepqoxo.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2kbckrfzw.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gt2dlzxwvyq.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gt2eqzeygvs.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2rdmekdqa.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2evjrgwfs.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gt2atxeekkr.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2fpgtezzd.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2pfpojbkv.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gt2jyxbikqh.html


<!-- 参考信息 -->