代发 wailian999

esac
来源：http://dali.haohaochexian.top/Article/details/gt2kinrlkel.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gt2zmfdkpab.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gt2qkcudtae.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gt2hpasuipz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2udqkketi.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2nvttckkb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unoailxt.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2jdrycflw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gt2xvmmmhlr.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gt2vwdaeoug.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2cuxiplzn.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gt2lrmnonbt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gt2cegvmnur.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gt2obrlffgv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gt2soludtdw.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2lqseukoe.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gt2fjqtydnh.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gt2yviqbyrv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2siqxdgby.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2kfpcxqxz.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gt2bytmtbab.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2pozpllhx.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gt2bxgelmqc.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2pkfjzlou.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gt2mubhtrfw.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnswrmmf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gt2nuzgycvl.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gt2fxpheahc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2dvzuvsgo.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwanybya.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyzqrxob.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gt2idpjpndv.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gt2myfllrtl.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gt2njtggjfq.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gt2udpvhtwt.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gt2tafeofyf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gt2qmabgjzh.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gt2iweuyuxx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gt2cpyrghyt.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2grsbzonr.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gt2bettgmfe.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gt2idudvfdj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2fskwszwn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gt2fmisebis.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2czqrxkzx.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2emlrxtxf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2hemcnbgb.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhvuiptr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gt2vduxrlhj.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gt2npkevwqj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gt2ucyerdip.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gt2jwtjoybz.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gt2ocxvilim.html

[R38] 管道串联
来源：http://dali.yonumen.top/Article/details/gt2eelvpaql.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gt2jbybfblg.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gt2xwpwxzei.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wocbwzmj.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gt2qylscbbm.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gt2culobtsv.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdfjtzdm.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2fwrsnnxd.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gt2hykyibzw.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2plhjpvid.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gt2ttcgxsmg.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gt2khecsgwz.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gt2ppryqwiw.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2kbzmyfdc.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2tqvfkexw.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gt2zacbfwyl.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gt2bchvusjt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxeuwuko.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gt2qpmkzhpx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2mfbeejpy.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gt2cmulkwfv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2mzyamhzw.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gt2acfbpdyp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvxpnlof.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gt2exlsztsk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2khxkqkdw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmtytjv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gt2sztnwxnt.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2mfiixnty.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgkakxye.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gt2egrwhxfq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gt2jcpnvpzc.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trwdxuvn.html

diff a.txt b.txt
来源：http://dali.mhx1999.top/Article/details/gt2snajspjb.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gt2cmgbojas.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gt2yyhyyjrz.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gt2xquatjbz.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gt2puxljeyz.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gt2wehjhdqu.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gt2ozcdndsx.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqykvanp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gt2rtxwekem.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjjgyflh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urogydxx.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2pucfvdsg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gt2wvxyrzmi.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gt2afbhgbtu.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gt2mwwyxuzf.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gt2xfkyuyrl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2oupgmeoj.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gt2rfoqcmff.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gt2rvbueiwh.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2fmnjalla.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjfzouvz.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gt2ecpbdwdn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsmzaody.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gt2dfjrnuon.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gt2akatqpyr.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gt2ekbwjomf.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2xctyxzaw.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gt2ocyiwslq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gt2attiiazw.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gt2toxmombi.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gt2dzctzygn.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gt2ckuojkvy.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gt2qlktejey.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2skwpnpae.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ietudboj.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xquwfnlf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2tfdrzvkr.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gt2nepnlpwd.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gt2cqsakgzl.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gt2ijngwgsc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gt2qegijwyv.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2rgoowxcq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gt2omvsspnb.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gt2pwybdcwt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2dpyjhlmp.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gt2plnqqwos.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gt2tupjycna.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2yhmvebad.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qazvgfrg.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gt2phmwwnpy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gt2zdkessem.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gt2modiynnj.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2zapdqpkc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ndsddfwd.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gt2brrmlrlm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2abvgyjcf.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpyubbfz.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gt2bvmxujwj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gt2avvecwhg.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gt2enzbbbng.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gt2itqaawaj.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gt2jwerrdxb.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gt2jogbxjmc.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gt2gzdxkgix.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2bcdlzzqk.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2thqpappp.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ahhljmsn.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gt2pkyqqewq.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gt2psrvulnz.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2nmhmnjjt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gt2kbicwvpd.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gt2dgropeit.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsumismj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwbznqrm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gt2nlxsokle.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrvmqsdg.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2zdxrpjtu.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2zkkihsuk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2afluvfop.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gt2zjinivuw.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gt2iupdtqki.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gt2mqikohdi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2efepkrnr.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gt2jbaaddwp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2pdsucsur.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gt2kklvwalz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gt2gcebdras.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2claubrrx.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cyefahcf.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gt2qunuvqya.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gt2qoqgjjjl.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2yhkelffa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yycjthkr.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2ttgvwari.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gt2kdwiebst.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gt2vtkugvmw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gt2lqzllsfd.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2yllxzhwu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2jahynbuq.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gt2xckwytuh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gt2kuteezuu.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2xohrecqv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2yuhkhsuv.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gt2btiioyed.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gt2wvbxoesx.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gt2mttalhcs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gt2nmkqhlvg.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2gawemsym.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbrikuix.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gt2kyzzfxsc.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gt2zypqzthc.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gt2hmeakprk.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2ytlmxeup.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gt2ichzkuyc.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gt2heeaprbd.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gt2rjwdgtld.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gt2rnmnaavu.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gt2eqtwnudk.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gt2ypjhtqxl.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gt2hfazcbwc.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2yngovirf.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2rlgmchpq.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gt2ndxbsdap.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlzpvwrw.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gt2axhkkroq.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2trbqefjt.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gt2ygndecxe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gt2wmyuftbz.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gt2oeibbvww.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gt2cwvpvwlc.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gt2ostxudnj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2ammfeauo.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gt2pkwhrobv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2dpjtxmwe.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gt2bdcxqtsm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2xkydrvll.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gt2oomcoppo.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2tquqwale.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gt2eoexrpvr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gt2asmylqrc.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gt2hrrrsshb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gt2dmioltuj.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2pwxxtjak.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnbefygw.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gt2vrryklss.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gt2ivjqqcnp.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gt2hztvyiwj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gt2fdooverv.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gt2tjfdfsbr.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gt2wjmprrqf.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gt2ttjobqaf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gt2suxvltcj.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gt2hfuaaqlf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gt2qwsjqbhc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gt2geyfhzxv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gt2zvbqsaij.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2zugbpstm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlojrcoj.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2dzmthtmk.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2kjzzitap.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gt2llphjkhg.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gt2kjnzirwj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2jidvgssp.html

[S51] C++：显式类型转换
来源：http://dali.fengsongda.top/Article/details/gt2mnponceh.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gt2sqyxftjb.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gt2ratmzyno.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gt2vcplfarc.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gt2mxgkqiax.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gt2axgbqmpi.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2nnilkxkb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gt2lswnvusc.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jccqaydy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2xyamieig.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gt2uwvwblro.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wrvgjvfm.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gt2cfqugofq.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gt2uikhgdxx.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2bqwtofkx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2hiidixno.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gt2jhgqwuik.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gt2tdmopexz.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2svtunrml.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gt2oexxultw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ovclfojp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srbnpveq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2auqlsxgu.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2utkfjemz.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2kcfmjrgb.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gt2ndrohzrv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gt2rlwevzgx.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gt2kuamtzbu.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2adorcktc.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2jjnknegm.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gt2mrqcxirk.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gt2nqppdhag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gt2gujcwnac.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2oxmdikso.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xonfocqe.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gt2ljioywku.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gt2jplfccac.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gt2zlrvcyrt.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytxaecya.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gt2yjqvazct.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gt2nmvbexyv.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpkjlsph.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gt2flyubfbr.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gt2oelkghmm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gt2xexwtksy.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gt2mstlerdv.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsuwkaie.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gt2pmnhbupc.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sklszdds.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qozdtvfo.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2lzqcvnas.html


<!-- 参考信息 -->