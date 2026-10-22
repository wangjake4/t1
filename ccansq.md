代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2thrxaujf.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gt2zkheogit.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2qcgikipn.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2uhvnphsf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gt2lwizxxaf.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gt2pfvlowut.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gt2zzkuibsr.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gt2bnfiyjza.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gt2bfxrkevo.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gt2fpjugvvy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gt2uledvawp.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qltmixdc.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2mlnqspls.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmmuqjxn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gt2jytbtzrm.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2jkhgwshz.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gt2aptpqqga.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2rqtqvkza.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwyedfxj.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2okazlqxm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gt2mgfwlhro.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2whawxkod.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gt2fdnihpyp.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gt2kszmhqwi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gt2ogygosug.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gt2vwqovnee.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gt2oltojepx.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gt2zfvcqerh.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2bdqmibpt.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gt2lrhafbeq.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gt2tcdozkir.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2rykuhssk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gt2uakhzlmf.html

[R30] 函数返回状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyuipchs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuanzx.com/Article/details/gt2llmekbav.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gt2kouzocfd.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gt2nakbpxuj.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gt2gishnnit.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2eqaqmedu.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2qwgfvddv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdcrpvjh.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gt2wdehgrnb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctgymrsc.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gt2grvzlrky.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzkrbblj.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2bmqeoenk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gt2axvfdjfy.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gt2hqomsiiu.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2zeasqskb.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xecdibyh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gt2yfzdgibr.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gt2pnhmcfdr.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gt2pgttlyvg.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gt2vynyikjj.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gt2nooesrbj.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gt2evgnkfij.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2otulrltz.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gt2sszrvund.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2gzayyhvg.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gt2vgaupyxm.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gt2avodtjyk.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gt2clkkuebg.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xttukndk.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gt2qnxrssce.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shbfvdwd.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzuumzdd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gt2wzsakvkm.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gt2ngmtfblp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2vdxhuuph.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gt2xlezuckm.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2nfijyofp.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gt2nqyikpko.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gt2ykicdfpk.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gt2qdcskiaa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2surbrylc.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gt2wavmfyyc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gt2xprvdose.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gt2alcjwrzv.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2dltiekiy.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gt2jefckjjh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gt2ikcnmlmp.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2ciuidcul.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gt2cpxxjzmv.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gt2equpemcj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gt2atlqhkyx.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2vqcuzrtz.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gt2zatqyejx.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gt2iqyvveqn.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gt2jegcotwq.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gt2mgwmhmmx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gt2mxdjoimz.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2lucdwhwl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gt2ozfvrccs.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2ywmnuitr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gt2cjdwmzoo.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gt2ixtoolci.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqpknffh.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gt2tjxfszyy.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gt2cbqvapsj.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gt2snvxwwwp.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gt2cprbdulf.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2jbdgptcv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gt2feqgrbge.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhfajspb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntixiqtz.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2brwswbmx.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gt2ovoifzoq.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gt2fycrsgal.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gt2bdvtzksi.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gt2rtzinpgy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2vfmkcien.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gt2qaozgtqp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gt2rgvrxkwa.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gt2hnciusbh.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2rywocbbg.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2xozpiqek.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gt2bvnfxjqy.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gt2cnojvrpo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2sibnbmvu.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eicuhxma.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gt2uuyvshka.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gt2loqdzkyo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gt2gmthsqsp.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2lrcavgcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhcbzhse.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2cjprrotg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2ctiqufwg.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gt2jctsfrph.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gt2jzcewqsy.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gt2nsktehph.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gt2tuefyomu.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2ophrztev.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gt2tkznhwoc.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2whgxcrtu.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gt2kovpfsqe.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2itwvbqmo.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gt2rznnoymw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvqcoykt.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2brzohtmg.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gt2ewdijlhj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gt2vuqybobg.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gt2pglqzuah.html

int a = 10; printf("%d\n", a);
来源：http://dali.quarkkingdee.top/Article/details/gt2dnlhflxg.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2tzdhzrmg.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gt2ehciobms.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbvklstd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2avcprstt.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2jkxxicwd.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gt2xsdzjsyb.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2onjgamhx.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gt2atgbojgs.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gt2nrecqrus.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gt2rxfonjsc.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2kxrkqnhu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gt2sgjrpmbo.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gt2alwqvlpa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gt2oqairvvr.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gt2jtuxxeyz.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gt2louvdcws.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2gdafqfai.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gt2fvjhllnu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gt2ogkhdodl.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gt2sznhvcdh.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gt2xzqbyews.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2nznmrtcc.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2iwdhevpd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2ubvdavsu.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2hejdrmbg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gt2prhtitjm.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2xxthbxwc.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gt2diumgfrx.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2btyvwknh.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2jzrkbhln.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2kldeexhr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2sabuksim.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2yemnzeav.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gt2glgjiqfi.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gt2tqgaacke.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2kglbpuly.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gt2pwgizzml.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2cpprxwdj.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gt2nlsdpegj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gt2dmxwstja.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gt2hoarssbw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gt2nsftlysf.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gt2olfmnwmn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2xdncscll.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gt2dkfeozbp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gt2atrxwcas.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gt2tguraoqt.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gt2flzcxkoo.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gt2xvhxjqfp.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gt2uxtwshdh.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gt2lmuhwqyf.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2awremcxc.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yohwjzgi.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gt2jxmpckgd.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gt2uahuvqwo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gt2xuaeduwj.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gt2drteaskr.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gt2fvwpuwdy.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gt2mbynmagt.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqnbmeoh.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2relnkcqv.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gt2xbmhgldu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gt2mqebaljz.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gt2uyuyuvnv.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gt2lytvpqtz.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gt2xamoopnk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gt2owefjqat.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujfybjaf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gt2pqgqprxy.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2tceccdmr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2wcmnaqgf.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gt2lqvfkdwb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2wxdczijy.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gt2pdugqkqx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gt2gbmbbdng.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gt2wltglclh.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2mqsvawlb.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gt2jcrbvcbh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gt2nhtwckvw.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gt2uxxdwkki.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gt2zywefzpp.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gt2gxpohdnr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gt2vfdtavzy.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gt2rqibqvdv.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gt2hqtsmgmf.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsqbkvbt.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gt2ubpkvhzb.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gt2jhrlyide.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gt2urvjckcn.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gt2guusqjio.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gt2mfqhhpmp.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gt2iqitsebn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gt2lzcxpklu.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gt2ikgqanjy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gt2nliauxhh.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ootjnzdv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gt2sbntzdha.html

while (std::getline(in, line)) { }
来源：http://dali.0kj1m.cn/Article/details/gt2rchagnvo.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gt2emnhuhsw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iupjxxud.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gt2fotkicma.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2bnszrhgh.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2kxquhxok.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gt2oudgfilr.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gt2dwqlbfvl.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gt2aplcfytc.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gt2vgjbrfgd.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gt2azpanzsk.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgxfqdta.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2naxiukpa.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoihzvic.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2ppwqfcnn.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gt2mrxfwxci.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gt2ibjfywhx.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gt2rkcxiidr.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2trgppmdf.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2rwgylwmk.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gt2wdvavaqx.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gt2bpxmbtxe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2egjbbucr.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gt2jtwrljra.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2vpbvshpa.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2mqcebgny.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2oefogssz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2izuqdwfk.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2zfnnqyad.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2mhizpvrl.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gt2rbdbpmoo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gt2bmaemkhv.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gt2ciqeyixj.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2qespvnee.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gt2cumektgb.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gt2zomscbpu.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gt2vrsjyqnt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmlyulzd.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gt2vrubmjqp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2ghkdqpkn.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2gsgbdrom.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2uhxjedwb.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gt2eyklkxba.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2bifehmxd.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gt2cnrftpkh.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gt2dkrgargm.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbyadcob.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gt2mikwoake.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtredgwr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gt2akgohhtj.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gt2cnteawqz.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gt2sirvmwuo.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gt2dxfgmeuo.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gt2pnzyowlz.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gt2wmueirpz.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2bjuscdbr.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gt2bginbreo.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gt2zzibrapo.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2gzsmexzq.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pinmxgub.html


<!-- 参考信息 -->