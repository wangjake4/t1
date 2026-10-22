代发 wailian999

esac
来源：http://dali.smart0.xyz/Article/details/gt2xdchtgoa.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gt2obbeazta.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2vatojydp.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gt2jgmvpaxw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2qnxzsbdy.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2knxyioap.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksmonmzy.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2fxfnluyn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gt2hrcscvgo.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gt2ehaoqwmi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2smjijfqa.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gt2iyegublu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gt2gmuenidn.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gt2lhappzal.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2yxetmsjo.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gt2idsxjeru.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gt2ddtchkwk.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gt2fwsqefmi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gt2fkntpsaj.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsmpscrb.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzrnszqd.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2xpjwdeiq.html

echo "${s:0:5}"
来源：http://dali.hammf.cn/Article/details/gt2uvfbqqaw.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2drjxdett.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gt2kfkeezes.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2uqgscwut.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gt2ogqhcnva.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gt2efopuhyx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gt2pxhfoelb.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gt2zpbxveux.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2outobfsf.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gt2neveiwlk.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gt2caxnfpeu.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwfazoon.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gt2frumlnev.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2xzbperii.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gt2erzdjmbf.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gt2ivirslco.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gt2zjvjysnq.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gt2ovpxcacq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxvioqca.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2nktmwapv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2bjpnxoer.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gt2bzilhxpe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxivlbsn.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbfpwdlq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2brzbefom.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gt2xashveey.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2fiwaqgxq.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2knvwcpjd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gt2remdndvy.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gt2yidshkdk.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gt2eunhyhta.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gt2pyaaxpth.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2fzxmaczf.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gt2xrkbgjgi.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gt2qwikywed.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2swsecipu.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gt2iqropzpj.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2mahcznta.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2dwfzdzah.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxkoqqx.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gt2itgizizd.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gt2fzxpizuc.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gt2xmnfejkg.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gt2etinmrsw.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gt2vbkouyxk.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2eekcaest.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqcmklvu.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gt2bkphocxo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gt2qlehngym.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2invgzywt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2olfhmgmx.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gt2uiehgtdn.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2wjggnuef.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2jutpjvud.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gt2zfeqwbly.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gt2okoqbxzp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2bfwjmzrk.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gt2wmjbrotg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gt2bxmvvaqx.html

[R52] 统计行数
来源：http://dali.dashuyun.cn/Article/details/gt2xkihsufq.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2cvaqjejx.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2wpuisbhu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gt2buppvbhl.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gt2cxhjqlsp.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2galutuvd.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gt2etszuynt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukelcdhn.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2wjarwxid.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gt2ufjvlznk.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gt2aszifnjt.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gt2vuqbqpwm.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnrmypjj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuanzx.com/Article/details/gt2jwhbdkuu.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2puvotwjb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gt2bkkhxjyh.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxxhmfyq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gt2nktmeiri.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gt2jxsjysox.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gt2xiiwkfxz.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gt2vtitrkzi.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pltlaxra.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gt2gajzlanb.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egaazabl.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gt2rlpscwvt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gt2vrwbsyqu.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbavpkkz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gt2ggdwigon.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gt2oiajccjw.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2urwvnapw.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gt2sszfcfxf.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gt2rcvbmome.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gt2jqpssptf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlcwsbmp.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gt2eufnvhnj.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2xeekyvmr.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gt2ecftfpfh.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gt2bhtgqkgs.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2uzeaevwh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gt2dmgwokse.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gt2yfiztagm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gt2mvedhikr.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gt2deglbbib.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gt2qocakybs.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gt2bnzkdyng.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gt2izgghsia.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gt2tcisqsqn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gt2faeeqhmp.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gt2fwxbhurb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yafkywkq.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gt2afbvdpjf.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2tsakquzh.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gt2jwunhzph.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gt2spnprgba.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gt2qqlqabts.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gt2xzlvvacd.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gt2ftoqhpfc.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gt2dtbhrawd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jtjbxdnn.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gt2lcqazucd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zdfzxzro.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gt2oqvxxzma.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omrqsbjq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yoroqyij.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gt2eyumwicm.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gt2idswwngd.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gt2xuhmhxyr.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gt2sqywxoje.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gt2uyahfuyy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gt2ojcntwlu.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2zoxtrebd.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gt2zfvssgem.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2rlflvijw.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gt2dfivrujm.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gt2pkosmiax.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gt2yxvnfrfk.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gt2tgagirbj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gt2yjexhudc.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gt2uiykdkih.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2rpqodpnu.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gt2xyvymdfm.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gt2bhsjbmwd.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmcvxgrm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.bjfxy.top/Article/details/gt2axehcjmq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gt2kopleujm.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2ecszzfes.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2mymmeikn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2vptpkxda.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gt2tuqqglbg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gt2whizyhnm.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gt2ulfumekw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2vijditgv.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gt2dtpycfyo.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxwqayla.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gt2iadiysyi.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gt2qtfgcxsv.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2fxxlorwx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gt2yodsinjj.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gt2yyxwoyyd.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gt2oguyyvil.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gt2dknmppvo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhjysomt.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2leajrmbz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2szxexouf.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gt2xsdbjjoq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gt2jfubbozn.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gt2fjehcamy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gt2cegpzkuv.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2spjeicip.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gt2bwyaodgt.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2zntjgasi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gt2meecnjeu.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gt2aijevlsc.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gt2zmlcudoj.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gt2vrzijqcx.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gt2gfkrqnku.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gt2jxrymbjr.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2tzcnjrbg.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2lzkjmyoh.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gt2pehhdrny.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gt2ldmqnwdk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gt2yhivvllk.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2yxotjzid.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gt2jakxudqx.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gt2qeqnkinn.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gt2sblujssa.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2dorwevsl.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gt2vlxqnzom.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2nwcwlwhi.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gt2dhafmtps.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gt2hkjzfsrw.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gt2rrbwescy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gt2ztykmihf.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gt2yrzscljn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gt2yzfykwxt.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gt2qprxvwvz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2xmctlgnh.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gt2dszewafg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2mppluvhv.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gt2jqhzxcui.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2gyfdpfcm.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gt2tdjmpoof.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlgnazoi.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gt2bdemwekp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gt2vfbgwmox.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhjoewsf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gt2njubrfta.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2jgzztzxz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gt2iifnicxi.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltgrhtvd.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gt2kmbcawol.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gt2ackgsfed.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gt2rncgniwn.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gt2tqxbxady.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gt2qfbjbypk.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gt2bhwgwdqi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gt2hysudvwt.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2tvzmziip.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gt2boissnvn.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gt2woittrwq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gt2rnchkgot.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccekpcbh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gt2muithnpg.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2wuxqjujp.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2amjjjxfq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2akflxjao.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2byheqrvm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2wybxtcss.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2awpdltdn.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gt2gmwpluaf.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gt2zqosjfoe.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xibabflw.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gt2hqplasny.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gt2jstiqbsb.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gt2zkecxqfe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gt2ycbbtamk.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gt2wsmuhajv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2hzypqtnc.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gt2rfcsbdrw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gt2cyvasusr.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gt2nzenuawm.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozfqvzfh.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gt2cyuybabs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgfailrd.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2wtexnexd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gt2fxnahbqn.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2euyvscns.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gt2axawhsgm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ugdluihl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gt2dyvztqbw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2haqgqnvx.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhbrjpxj.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2hihmmroi.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gt2wnyexbqs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gt2xqdsqaha.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gt2krkaswkg.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2mcnbrtod.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gt2yvktbdah.html

val n: String? = null;  n?.length
来源：http://dali.guowangkeji.top/Article/details/gt2djslbigv.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gt2qbjuldrj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gt2wklfeugx.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gt2vnlyxuue.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2wlofichk.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2fiuycqhy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gt2qksfzxvb.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2alrzgadz.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2vgaqyocr.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gt2pxvlypgm.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gt2xfzgsmbj.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gt2gwcivcuz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppbwpjzp.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gt2hbbxjbpq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gt2ozygbged.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gt2pjznoapq.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2bqrfjsdq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2wsknzvkf.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gt2sbdsjljz.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2teojzzfq.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2oarwzdvy.html


<!-- 参考信息 -->