代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gt2iemxzayd.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2haruptgv.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gt2uiqwlpxp.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gt2efremhtb.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2hduyrscf.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gt2bniczwmn.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfsxhyyj.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gt2iaavhtir.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gt2krxkbylc.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gt2apowrqoa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qydeohfl.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2iotjqxqm.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gt2rhryrmmj.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gt2stqjouml.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mfqdpbpj.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gt2fsahxfdl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gt2aqosnyew.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gt2gwzdywpb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2nkeykigd.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gt2dsmbpife.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gt2azhrgack.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gt2ipzhpnim.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2ccybvsyg.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gt2ljmsffvt.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gt2xyhczaav.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gt2loslewzn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gt2kmsofqax.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gt2bylwjbvb.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zebwctqv.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqwqbpek.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gt2exrqnwrs.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gt2yvfgemme.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2yninccka.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gt2btrftvqk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfalwcnf.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gt2tcmppubi.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2uvkujtbl.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gt2snswyahc.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gt2xvbvlcuk.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gt2citjssbs.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gt2zyiucedz.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gt2ultipjvy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gt2wevjqmxy.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gt2cmregfvj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2zqbxcqrf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uixojfsr.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gt2qfjrwihh.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gt2mefxyeku.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gt2muqgsfbk.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gt2qndwpjtu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhesscfr.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gt2foynfoor.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gt2ocrzehqn.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gt2zqojdavc.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2iquuqxnt.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gt2pcapspjp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2utqdbfxn.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gt2hnhltcmc.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gt2snnnuoum.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gt2gxnuafxb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gt2pzlifhjs.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gt2skkammdc.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gt2vxnuzkni.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgnwcied.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gt2odnxmopd.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gt2xvrarxiy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eoxjadqw.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2hreembzn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gt2ndxoimsc.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2cabijmsh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gt2caxcudkz.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gt2jovclvzz.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gt2vplnwquu.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gt2ikgqqlzs.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikdbnsng.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gt2ewdiwrkm.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gt2ayjpilwx.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gt2yslxifif.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gt2zwalftxo.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gt2ostxkgwl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gt2gghvzpfw.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqtytsde.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gt2bzmybppb.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiatvrtf.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgmibuxs.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gt2yzpjccym.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mppoagli.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gt2ngbazvte.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gt2cexbrqux.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2ovxqxigt.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gt2zganmuss.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2grattbse.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gt2esebnbxp.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gt2yymiwgct.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2duazilhl.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gt2rfpwxvzc.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gt2tluifkbw.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gt2ujmtiqar.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2dctkkrmo.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2hdpckqih.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gt2dguxvsmu.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gt2fbgklyat.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2zgqdqasc.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gt2flgvogmn.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gt2scgcacmg.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkefyykr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2dvavqegk.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpmjvaug.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gt2ckabtoyq.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gt2amtlxpgu.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gt2tdnkzlgz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ysiwmdhy.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gt2jeakbjhr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2akutjtfq.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2bbxstnsg.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2uagxooje.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gt2hylgeewt.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2dhbzkmpz.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqwqgudm.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gt2mxlefbcd.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gt2stbvhwqj.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qinjmhxh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2otgohzua.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gt2ldaudlyj.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gt2hieayynr.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2jlluhukj.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gt2uzhaaluq.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gt2qcusncch.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gt2iyazcgjb.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gt2dgjrohyo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gt2qbsueuif.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gt2lmbdhbzo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gt2pfjvdbrx.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gt2lfrmodlc.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gt2rvnzktga.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2paeudyfm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gt2bgpiedjk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gt2qucqvdsr.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2sivenpcl.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2qfjsztrv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2yjjddtnn.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gt2ghrrpuuw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzttwzgs.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gt2niiqdrrf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gt2jwfpecbh.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2dbcmwyoa.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2jpczrerq.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gt2uwhwujfw.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gt2zgaqdkez.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2wcdsieiw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2vtqsikca.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2hqptygua.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gt2ohkbmpyg.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gt2khqcrqol.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcqhnwoq.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gt2qrbtulab.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2aumxovvk.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gt2wyuzlicu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gt2bfoxbejv.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gt2ulitjzfo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wczkicyt.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2cxgjduua.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gt2lwejsylq.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gt2mtzfbyem.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gt2jivtlkkt.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gt2fyayhwgm.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gt2sanomstp.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2drkrasho.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewdcdvey.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gt2biymspuj.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2nwmllpjc.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gt2dwochulf.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gt2vhqdbsly.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gt2aiodnmwg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gt2gqgxrmeh.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gt2owwykawb.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gt2flkphvmj.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwogekvt.html

#endif
来源：http://dali.nwbrower.top/Article/details/gt2zukaxiqs.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2dnnxuqnp.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gt2yivtkixp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2aacamdiu.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gt2aacmjswq.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gt2nsqkxwvl.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gt2zdeipbjc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gt2rmmesnrf.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gt2dphwktzc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gt2fryhsrof.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gt2ajkmymgg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2ahgnsiua.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utzrtkrn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2yknexroq.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gt2smoxomgr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gt2foxtugqe.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2tjweouja.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gt2flukubad.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2bvmegymi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gt2tdezkovm.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csuokjld.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gt2almdpwcm.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2ncuamqbb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgnmvfyt.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gt2tbienyng.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gt2ekuklogv.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gt2vwysjeai.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gt2tfupsiif.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnupoxgf.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gt2evvdljkl.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gt2blfinxfn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gt2gsxnueoy.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnuhjftt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gt2wkybuvtj.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gt2jjppedqk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gt2zhhxveuk.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2qvldqzti.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktnhcfxj.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2kkjmifol.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gt2weqfpbax.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gt2ytsaqrpe.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2guipepzm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2ltpptvmb.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2pfjchukh.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gt2zdhkaqaf.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gt2wniniwrv.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gt2xsbaqzrm.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzwhzxqz.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gt2olmrjvun.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gt2sksiejmz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2myzckabn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkisnhc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gt2ltlkxccu.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gt2nmmeatnq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gt2ejhypqio.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gt2jskvgsjp.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gt2yqsciuuy.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gt2qsfoprks.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gt2rlqrtqvs.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gt2lsmvfhoy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gt2vbozdclz.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gt2hjgfyito.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gt2mrwdvzsb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lrbimefy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gt2pywxmvpk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpvyndka.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2fctzjsko.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2whcqzjyh.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gt2gqthmerd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gt2rbfvkrck.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2oogyqauo.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2lpfatyar.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gt2mutpkvpo.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gt2monkkgnq.html

[T05] Kotlin：when 表达式
来源：http://dali.zycfv.cn/Article/details/gt2mpbtbwrp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjkidsbx.html

[T06] Kotlin：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gt2kluvsjiq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gt2qidlobxi.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gt2avmokwrs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gt2hkediyox.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gt2ktazpynu.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2jgmfamgm.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gt2cmovdclt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gt2cpinjqez.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2nvsxvewg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gt2hhmcdpjw.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwepeaiw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gt2vhvgpfvj.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gt2xnvozrwm.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2zcplyutf.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2yjhnexvy.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gt2knrpcltm.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gt2dalbmxsa.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2jqwxouyu.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gt2liqrjlte.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gt2oeivlavb.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2wxfxlkdj.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzbujkhp.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gt2gnumddnz.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2aglgfwcv.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2ooazzfvy.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gt2rkwrpwno.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gt2spweuvap.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gt2hwkdgqva.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gt2zridxima.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gt2skwjkapb.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gt2xfrrluig.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gt2qngfuzbk.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gt2ezscalgo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2ibmjyfqb.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gt2yoaecdid.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlvutmkd.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gt2hfgtpwjn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2agrnpxbw.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gt2nfulzkxv.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gt2bxpazzgf.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gt2mahnjjoe.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gt2yqpookvo.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gt2krwvzvny.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gt2oyjwmlqk.html

[T28] Swift：枚举
来源：http://dali.pycfn.com/Article/details/gt2cupfkxik.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gt2fpywohdn.html


<!-- 参考信息 -->