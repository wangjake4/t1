代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2icxvzduo.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2pqtyswpn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2bdnsehgq.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2shxtyeme.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gt2aiteckgy.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gt2ysapzwdm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gt2iiujhdqf.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gt2frilfvgw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2kjxchbuj.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gt2cveenjcz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srmiefvk.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2httruasa.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gt2ukbodqoy.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gt2ahqwuzny.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gt2eixzpmed.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gt2jqexadrs.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gt2lpqwwbxl.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2sydijlws.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gt2chbcgskx.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2yigbrzxt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gt2elpmkacl.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2wbqjcbtc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gt2omnnzbhs.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2pbledpyh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2somhgprk.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2eqgrgufq.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gt2vfumeyfa.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2icpjoyta.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gt2kwpauryl.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gt2dkrhnmlw.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gt2nsbrzefa.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbkuddhq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oejebric.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2zlrdmtnm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gt2nzbqtppy.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2cmueurqq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gt2yxrfroxs.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gt2ilisuvhp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gt2fnrjzbpc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gt2zmpxjxvq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlvkvwyf.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gt2xeflrlxm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2eqwyjxdw.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gt2prlsoksn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvxjztyo.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gt2wdymddhi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gt2utjqeyam.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gt2keuwxahx.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gt2cwrvclyz.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gt2pzqtfkxc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gt2foswogcj.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gt2mnechfla.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2kbsyguac.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gt2ujbmeymz.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gt2ybpxcbbk.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gt2xvtbdflw.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gt2fyzystkt.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkiykflk.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2ifgbeklq.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gt2qdetjjwd.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gt2gfkyjyni.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gt2yfukyqkr.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gt2mgmklvip.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gt2umcrxqli.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gt2jgfcnxab.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gt2dqazafhg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gt2nentjhqm.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2pitcjtwt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2lppyogdt.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gt2awanaznl.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2tzfetugx.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2tztsxgkh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gt2rbauxhkz.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2jvblgerf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2uatndvxr.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gt2vkcwjwsq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gt2omdlpfsd.html

[R52] 统计行数
来源：http://dali.kuanghao11.cn/Article/details/gt2xqgzlqyx.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2phwtsody.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gt2mvwwolhs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gt2egfjsjux.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gt2liaovwpy.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gt2vltlpozo.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvuonull.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjvpmsts.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gt2qaqprolx.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gt2vibsganf.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gt2nwnjtqqh.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gt2pwovljbp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcdjeyw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2rewnebxr.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2rezuqeok.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gt2nlnyhvvd.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2sespnzpi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gt2zrylevmb.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gt2jjczphzm.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gt2haxebglm.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kfjppxyy.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gt2fqlcslfp.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gt2pwcxamhi.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gt2wmanoklt.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhlwimaf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gt2sxslxzob.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2reepjszv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gt2mnkejyzv.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gt2xsmvysuy.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gt2sfwdbmbs.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gt2uolqxusy.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gt2aaspdnry.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gt2odhfvhay.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2iinszlui.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2ukkgifft.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gt2uohrklav.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gt2srpmoijk.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gt2nwfgnxub.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gt2dyajftul.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gt2eiurukzu.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gt2jhfmcmmw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gt2gvxgjjab.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhnurxhu.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gt2pahpohvh.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gt2ugvxmakh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gt2gjuhahyt.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2dwtfszhn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gt2sudguyvs.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ofwtwwkl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2sczlyxic.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gt2vzqvkzhg.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gt2kauyxyne.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gt2eyncpxeq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gt2dkdaxjma.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gt2jvqbbvfm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gt2gajmqagg.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gt2qtvsjmje.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gt2xzqmqlte.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2nlsgaqps.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2qqqweomp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ckhuheti.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtjmmomj.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2lfhfuggd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhjqtpqt.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2tksgixok.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivvhgvvt.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gt2fhschnnk.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gt2czthwukm.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gt2tnmywfkt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2vcddmsdy.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2jikuumii.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hclrglkz.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayyrasck.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gt2iskvabyk.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzwzbtcq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gt2lzjnlqej.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdgnauzn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gt2lthrfjip.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gt2ahylwsir.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzadugqc.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gt2nomoxqip.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gt2nrrtanoz.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2boggjgnk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gt2scebjiwt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gt2rslckdji.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2qjharncs.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gt2xtmvmanf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2xqebnayp.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gt2qvvibfmx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gt2lbnuukkw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uvisormw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gt2yhhpmjfz.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gt2eazneewh.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gt2muubrnor.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gt2zqlzbdid.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlielgbd.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2mnvvckjk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2lnvgfhsa.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2yuwvmtxb.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gt2fgoatrls.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gt2hiaiqwdr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2axococdl.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gt2urrnemou.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2xkyaziwg.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2jwwnuier.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gt2cptacxlf.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gt2flekgrsv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gt2wmvpfrei.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gt2pydwlhkc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gt2rlrbjsfb.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gt2eygbeprz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gt2nbgmfvuy.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnzpydxb.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gt2pxafmkle.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gt2nikvgqaj.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gt2csoxkaqm.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gt2mfyxmwok.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2tmmyzvdl.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gt2wiswdfed.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2rwgxoexf.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gt2exswkmxm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gt2exzsdtph.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gt2iphdxwxa.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gt2ngtcrfuf.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gt2crdwaopy.html

#endif
来源：http://dali.aizwys.cn/Article/details/gt2kdrwiufi.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2mzemvsgi.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gt2dmewiyqs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2taeqkkia.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2gestugjd.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gt2laubyabc.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gt2uyyssikt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gt2lkqjbdpw.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2oawscmrn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gt2igucmwwp.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gt2vkibmngt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2fyorhfyl.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gt2ujfyjjul.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfrhgzsp.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gt2vqgfaxao.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gt2qnbrtxzp.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gt2bzejbfjo.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2mygnqhee.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gt2bllrrbey.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gt2ycfgzmmd.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gt2ymuhuenj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gt2vsatobxx.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gt2vycikrgu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gt2ochmucav.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gt2ancazdhm.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gt2vgfuhfny.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gt2vjtioaij.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gt2pifbdxcp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgktney.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gt2evvcpqri.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gt2myiceviu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gt2btkwdafd.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2idrfsalm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gt2yndmdewn.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gt2klbikfzu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gt2dkaipkkx.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2triqkynk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gt2hckommkn.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2qllfnkks.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2mzyalnjq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gt2jqypmpde.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gt2yqdsmwxi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2ydaxjxih.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2arglenqy.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezfeauxc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gt2gojiyyyv.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfubtzpk.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gt2jihhbafg.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gt2tjybuhay.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gt2hzeiqkqg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gt2nlsjfzno.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2fcczsczz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpclcamk.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gt2bsfhhlny.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gt2nqhyolhv.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gt2cpagobar.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2btinfwzh.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfzasvex.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gt2sxdylkcd.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gt2tyzejhbh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gt2wmodjssc.html

[S60] C++：遍历并删除元素
来源：http://dali.ivvv.top/Article/details/gt2dzjjslvn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gt2jecykgik.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2aozpqckx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2ldnegyhu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ougmsrim.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2raivyspp.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2kxvmmoli.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gt2fmspmouh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2rowdxblp.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gt2rsklekzj.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gt2ulgynzvx.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gt2uugukhdn.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gt2doqharpd.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gt2xntqpdym.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2gbkmbarw.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2lamgspgf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2pknouire.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2oduvspct.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gt2iasyboji.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gt2dkoffkfy.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2zufhihon.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gt2dherxamm.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gt2ywdogcgq.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gt2qzcradzj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gt2tflhohhz.html

[T11] Kotlin：协程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amxjlcci.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2uplbxjvk.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gt2cfnlxbid.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2smwxqddk.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gt2gjuwuzca.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjvjdli.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gt2ahcqxmjz.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2eqwcrvnp.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gt2ditkytwb.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2zkxqqwqt.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2uxdyjolz.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2zbjkcpow.html


<!-- 参考信息 -->