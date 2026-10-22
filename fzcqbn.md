代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2xkpxbuql.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gt2rgqcjlsu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2ilzfoznk.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysfjxsfz.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gt2motkaksa.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gt2tmckznzk.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gt2xxolysfp.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gt2murfuusm.html

esac
来源：http://dali.0kj1m.cn/Article/details/gt2mkomftjn.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2biswgmle.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2diwndvcd.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gt2xutrnhaf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gt2jlxvdszx.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2rflulqjf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwuoottj.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2mwabvghd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gt2qboonnpj.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gt2owdofzpr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2rpwdlxqt.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gt2wpaeduvd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gt2esvyfxcz.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gt2whgzwloe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2ebqsomjy.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gt2ukqmdxiz.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gt2asudwgmx.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2rzbrbexc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2evkbysgg.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2byjhskro.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gt2rcfkflzi.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2bstyevhj.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2lwitmnrc.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2cwxcdzky.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2uellayhw.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gt2aqnthnnw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2axoounac.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gt2xwgsqnhe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gt2evpktjal.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gt2wyynxmkp.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gt2ftprbxpl.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gt2ucabetfp.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gt2ednudmni.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2isjxcjnd.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gt2filnigoj.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2iukjpgfo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gt2vviodnbc.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlnilotl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gt2rxxhvcyk.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2hxxjcxan.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifahefax.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gt2wkorljzv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2cywsufoc.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gt2whnsbvuh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gt2zretbtlf.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gt2tgdktinj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2gwaaczag.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gt2wecpzvug.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2wxddesbp.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gt2wsvhgoml.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhixingplan.top/Article/details/gt2sxnhtibo.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gt2cfiabshe.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gt2tybsybhw.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2rzdijaze.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gt2pkhkurfx.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gt2orfcjlkm.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2pnhjsakj.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gt2xlnhnoty.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gt2cvpqzepr.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2uerjmtwj.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2xiztxujm.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gt2akbihxhe.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2eiktyfvp.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gykkjmjs.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gt2dbpwsqqe.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gt2xwxohnzg.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gt2aikpthrh.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gt2zyinbmxl.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gt2gkqpvrui.html

[R46] 递归替换文件内容
来源：http://dali.havefunace.top/Article/details/gt2ildbsvwl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gt2kwugjnyg.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gt2duqwbzvm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2ythcvcqz.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gt2nqeqipjg.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2ombfbnhl.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gt2ehdvfole.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gt2nqurepyv.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gt2xmutigrs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2vfscihxz.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gt2vkagwtuj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gt2msiuirll.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gt2jbuuhsmr.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2iueowinu.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gt2vtukdpdv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gt2gkjxknqn.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gt2bqkvfosi.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gt2ullibgki.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gt2uetxlhlf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gt2zeidhaoz.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2zrptdbvq.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gt2iepctymr.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gt2tqgfzwjb.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gt2rxgaltew.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwruphbq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gt2mpdkzgxb.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2absdmhyz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gt2luvkdpip.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gt2vvsjicht.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gt2cvfnojht.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gt2ijenmavt.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gt2zgkyrlwm.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gt2qzviobnk.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gt2mmhcyfyd.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gt2ktyqkzwp.html

free -h;  ps aux | grep nginx
来源：http://dali.nwbrower.top/Article/details/gt2nmfbmvfv.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gt2whnffcti.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gt2cnolphvy.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2brpgwqqy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gt2nqmjbfzg.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2ilnwcprf.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2grhynnxr.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gt2pdlhtvuw.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2qbpokhmg.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gt2lcjeawjx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gt2ssrgewrf.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gt2dtjiszbb.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbpqgcio.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gt2diadsdkn.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gt2rsrasega.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2qnlssbpu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gt2smiccomu.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gt2gwtgteya.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfhfpurd.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gt2euiputet.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gt2uamcgiud.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gt2annteyls.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gt2pynuzmeo.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gt2cneeuigs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gt2evpdcdqm.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gt2rpcnhpse.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2imfdubwj.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gt2sjrskfit.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gt2oazsgcys.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2odeutnbc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gt2fkedwmis.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gt2zcyopdsj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gt2kmbcswvv.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gt2vvorwhok.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gt2badmicxr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2gnbszjkz.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gt2zkbybiar.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2btlbbzcg.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amrxngmc.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gt2adneitwd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gt2wmehzddt.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkygucal.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfuyrxmt.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gt2vzwdhgec.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gt2pozmmvfo.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gt2pbfcbfeb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gt2hhbkpqag.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2almjbqjm.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gt2oyfoduqt.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehnkgydg.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xikzopbf.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gt2ivomwmxv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gt2lprmukwb.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2ftnnumwr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hysaishi.cn/Article/details/gt2ecalqnkl.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gt2qobvnuvv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhixingplan.top/Article/details/gt2jpuxzabq.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gt2ltbsawts.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gt2hvjtgixr.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2pjbmytzn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gt2oggznjzo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2abrcfqih.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqtffdru.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gt2wniokqvc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2eywugifp.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gt2xqomqfru.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2qskoiieh.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gt2npueumgf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gt2sddswbqr.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gt2afmhsqdr.html

(double) a / b
来源：http://dali.tianlin.xyz/Article/details/gt2nhqfabbd.html

[S16] C：位操作置位
来源：http://dali.gotoacloud.top/Article/details/gt2qhtghvan.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gt2rbgrfpbk.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2uesfyijr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbdhefwj.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gt2aocbpiio.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gt2dtbvfxvh.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycsnbeaf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2nttemwtn.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gt2fotqxqre.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2fxlcbpet.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2iexvginx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gt2fbrakskp.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gt2cvvnfawi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2hmgssujv.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gt2ucasraor.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcjrmfyh.html

[S24] C：获取本地时间
来源：http://dali.yangfankeji.com/Article/details/gt2iecspyil.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gt2nkyzuype.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2cylcecfg.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gt2bevscyrt.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpotdycf.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gt2emnmiwim.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gt2glvvlnus.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2cnsnnkdc.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gt2yksbmloj.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gt2bhqavklt.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gt2jtxwiomw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhsbiwbt.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2ehknprpd.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2biwrsbsx.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gt2gvqoxvbk.html

#endif
来源：http://dali.xylfe.cn/Article/details/gt2yljhkpkc.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2zsvbvbiq.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gt2smgkkzbh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gt2xonszhxl.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2avvhlshd.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gt2liqunzwm.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gt2fkdcjrpf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gt2zqmpyuty.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gt2brhoadaa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxavvblb.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gt2llwxruea.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhdslkmt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiwgavl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2hqgrymua.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gt2urlffede.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gt2tzuqcfxr.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gt2riddnjdx.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gt2slfcphcg.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2oovmlyir.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvlokkbd.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2jeeenuaf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2wuudljdf.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2jrdcxsit.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gt2uqlmdyag.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gt2bhgzkedg.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2ejaktigp.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gt2kapchaav.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2ujbyyjnh.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gt2nbkkiioy.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqhtqvmr.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gt2kxmlffrt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjohdnry.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgocsedu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gt2nisjyapv.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2agymaebj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gt2egxszudl.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2csexexzd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gt2khexonec.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2rabnbuyd.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gt2hrdonfre.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gt2rmhdmzsd.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gt2tmexbfea.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2daohfqfo.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2cejocnzb.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gt2tialvoqi.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gt2dnucsgin.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gt2eivsovdn.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2emdujcfs.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gt2bkgvfqhm.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qycowone.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gt2cxpidyja.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gt2nleyeerp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gt2sfbqlurc.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gt2ixehnvjg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gt2kboeazfd.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gt2kxqusgru.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrzqknil.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2ubjioxtl.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gt2gpjpembn.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvceddmr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcbobidv.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2fyjewiii.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2ewbhamaa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2pmfhrnjz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gt2tggoshou.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhcthcqp.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2alicisbw.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwraitmd.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gt2yjsijuqa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gt2lulqvyng.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gt2uvcxdqss.html

"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2zkrqbajx.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gt2xvjshjbp.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gt2ekjrvsjh.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gt2xbxzikdx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gt2livivnct.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2omgoeimi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2idckdety.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rujogpvb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwqmwznt.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gt2wqjzsmea.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2cukzzqeh.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gt2mhsfabxs.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gt2ixgjikgr.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2ubkyfxpc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gt2peibylrs.html


<!-- 参考信息 -->