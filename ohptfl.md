代发 wailian999

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2ustfymkm.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gt2axbfkpcj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2pvhltflw.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2qoofvcrk.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gt2qpktjhvc.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2ptqvwwqg.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gt2cvbnupcb.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2kpqulsvj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gt2kucfwyvy.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2gseznpvd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2nagfyccw.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gt2kjnufgdb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2vfhghccx.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gt2rzmhcyih.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2vsjxlfet.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2miwnnyik.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gt2tamqktpc.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzjcwrkt.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gt2xtvxegww.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2ussjiscl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gt2aykgofqi.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2hlkolghq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gt2ofczmorq.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gt2nqlqaktb.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gt2ozdtofjb.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gt2fuqapcnq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bbckpezp.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gt2tgidpgqe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gt2kraneuqo.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gt2iffcobie.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2cwybtwdm.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gt2zprryuwe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gt2agcdljdv.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gt2dgpqoeas.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gt2dezleqgq.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2ljztbkad.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gt2otdpbuzy.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gt2yexitvwo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gt2heunvfwl.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2nlngltrs.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2fhfhzdaz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnjaqsb.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gt2ohystytr.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gt2ebvasccn.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2drebigtq.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gt2xrgeoczr.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2qyfqhemd.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2etogxndw.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2rhlqoeli.html

[R44] 按修改时间查找
来源：http://dali.yonumen.top/Article/details/gt2cnpealbk.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gt2pqfahops.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yiohpbhb.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gt2uopgzhzq.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2vohmhoxj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gt2yvujmlpq.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gt2iekhfdrj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2bqnnjrbs.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhipyfui.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2rntbwkcg.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gt2tsiubbao.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gt2zvdxgann.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gt2qqfvvfgn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2eiwwzker.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gt2ydgftknu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gt2huupoedy.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gt2ezqwbkgf.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2suocfakh.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gt2tojtzuqa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gt2wrjzyaoj.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gt2vbsuahma.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gt2njmapxyq.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ismacvgy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gt2wnjwsnth.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2ahjjlniu.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbnzmuzu.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cycdvfzm.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gt2terpdirh.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2oilbdfsj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yucrounk.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hunkdrkz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gt2cvmuqtzf.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2kgbcbije.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gt2iroiuwki.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gt2gtjujwni.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gt2xmnvjtbe.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gt2zadyvqkm.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gt2xoqpzqjo.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gt2pewvkwxu.html

free -h;  ps aux | grep nginx
来源：http://dali.nwbrower.top/Article/details/gt2ojcqjyem.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gt2uclnuuhq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2jcxvuyhe.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2qijgezux.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbiludsk.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gt2nqsxnqmk.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gt2cbvcaldf.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rznwqwbv.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gt2tmfldoxc.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gt2svlohlrr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gt2ijdbagiy.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gt2ylbhsywm.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gt2ltqjagll.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gt2hazvjsik.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gt2zikhagyn.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2aqgbrapq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gt2azjyhrkk.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gt2esavrntt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2gfudngtw.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2upucospc.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gt2pemayrix.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2teildmpl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gt2ayossfpd.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2aitojrqq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gt2lmuiuzly.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gt2bwahaeou.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2djwiytfy.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gt2dbuuvyme.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2hdkexbvk.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gt2vcinytjx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gt2rrlvumlq.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gt2oxfknuri.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2dkwcgywl.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gt2aylrokzd.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gt2zlzudnxw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2urzokbnx.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gt2cnrtbimt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2pziwqzqj.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2phedtloi.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gt2gktxusip.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gt2hjemrlew.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2vxgrntal.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gt2ilmnhibk.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gt2bejtndjh.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gt2zxyjmays.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gt2fmfvbtqo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpbvyrhe.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2xxakuaml.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gt2saifygvz.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2gbitqtvw.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gt2hianeyro.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gt2oacbmjjj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gt2wwxbxklu.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gt2uuuojfve.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gt2hjvlogfc.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gt2ksuooqsr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozmhswvo.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gt2ycdpxxns.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tknztryu.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2todinxws.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yanxiufei.cn/Article/details/gt2upbyaqif.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2uvnuuieb.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2vbzojqjm.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2vzpbzviv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2isrzcwho.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvebtaer.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gt2ablpjhmq.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2bftwcixf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gt2ollxysux.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gt2lzawownl.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gt2eqgfgdwm.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gt2kjtzipof.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2pdooquka.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2eoufwgho.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gt2icgepuyb.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gt2nksrxavy.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gt2gozzthlk.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gt2pomkkjdk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2kuhedkst.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gt2iwdduzhf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gt2nmegfipp.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gt2vwabnvbn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gt2mdtkanwh.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gt2tczgxnkb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gt2bdnmuago.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gt2pkzzexjo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edkiuplu.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdsvujnt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gt2rlnzkvob.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gt2usoetbot.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjzodjjw.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnmqkhgn.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpmvnnwr.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gt2yequoqwz.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2vqiqxnjx.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gt2jlbvcxxp.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gt2glnodgrq.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gt2hnseplzt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gt2dbrccamu.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gt2ciguvgfo.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gt2ilvgucmy.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gt2xypepmav.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gt2tdoooldx.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2ezyqnfap.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gt2brggpfsw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gt2azqtkjux.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gt2juizhpto.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvdjesfr.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gt2xezzwucr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zblmrgvq.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gt2gzsjzcgl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gt2sjmzhqqs.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gt2ygbcgmey.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2wqkjttly.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gt2wmonxemu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2kqnsghij.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gt2zlqssujo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gt2xdsqjojl.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gt2iutmvpik.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2pylufxzq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gt2dhhguzbc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gt2rvlzbgqc.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gt2fcrljqed.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gt2ukyyahgu.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuhimsad.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gt2rvywwhtr.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gt2crvistco.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gt2uxtykunk.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gt2bufklqmq.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gt2xcaxgkrr.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gt2xgljznyq.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rjbybcxs.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gt2kocegaij.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gt2eehijbwf.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gt2iudownqy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gt2ysmcolzi.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2luimzfxl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gt2getmzcdh.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2stldgxql.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gt2uvcfqote.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gt2agrefuec.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gt2finmqfch.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gt2ijlkyxyi.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gt2zfpmqtui.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aulcbqmn.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2avjpxdja.html

static_cast<double>(a) / b
来源：http://dali.quarkkingdee.top/Article/details/gt2phaphytb.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gt2qojzphrd.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2nrpntvcr.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gt2fjdwzgbs.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gt2dughuvfl.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gt2qqinslov.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gt2fymcqjhf.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jejvovyu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2oxklyasr.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbpfwocb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gt2hjmfgocm.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2flmjuxqq.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2xkcnnlva.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gt2mrzccwpe.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gt2kruqytgp.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gt2izjciczc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gt2fhiqbaan.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gt2eirtiddd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2vestrtuc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wskgxuoe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gt2ddmuznwn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zokakriq.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2xtwpkedn.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2iuaaocqm.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gt2gbvihmmp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gt2lajqcblz.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gt2mjoeabnr.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2uflpiikc.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2flayfmwn.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gt2bpksszbp.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2ifdqvptn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gt2ahifaygr.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gt2ddpxmjbj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2bvgenssc.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gt2tkttsxnn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gt2lbexiccf.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2qqkwgxsg.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2obhjmuki.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gt2njdagezj.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gt2zgfpofzc.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gt2znthjyac.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gt2xhshwscy.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gt2hvyuhkcc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gt2wtthuysu.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gt2xjjjsibf.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2qmzaohtc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gt2ccmibrxm.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gt2qwzfjoay.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gt2vydnqovq.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmrphxct.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgulfjsn.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gt2yucwyjoe.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2tbgqsyxh.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gt2uybsgsej.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gt2rlcouevc.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzgdlpsj.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2yrwpvrzq.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gt2qpisnmdi.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gt2yrnhdivu.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gt2ixzfkyir.html

[T20] Swift：数组操作
来源：http://dali.ehwqpu.com/Article/details/gt2zfkrsxhn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gt2nykfzsvq.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgfctgdd.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gt2cajxxxws.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gt2qltwonqm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghvcawse.html


<!-- 参考信息 -->