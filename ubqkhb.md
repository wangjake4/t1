代发 wailian999

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtdwgiywkl.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gtsmjecijj.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtfxifwnkq.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtbofojgpi.html

esac
来源：http://dali.sweek.top/Article/details/gtoeemtufz.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtvxrirqap.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgufenzy.top/Article/details/gtgzuoklan.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtyqjehzoz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtagrofgqt.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtucdmayqy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtlgvuawyn.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtyivhkocu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtotilswlc.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtfyjmhknu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtivockmrf.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtwhzgfmgi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtngyiysaq.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtvikmdymc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtvnilayxv.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtlvihvprf.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gtlbdpeaza.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gtjtktrglo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtqxfidcry.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtwjspctdq.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqktlrcoy.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtqekisidd.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtwyrcgmsv.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtlhroesps.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gtnfujbixc.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtrzrxiopv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtggoqdiaj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtqazhwzej.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtnquiaeyp.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gtzsjtcbmz.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfsjfvwe.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtbdhadyis.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtxebfrvuv.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtyqpkevrr.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gtlfsgoeny.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtxtmpobuc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtqnwejflz.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtmlkksboy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtllrnlrbr.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtoqnfqoms.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtieetjdgd.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaamrerg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtarpjwtmo.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtdgqyyumu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtnsjguhiv.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gtmuttiove.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtwsxlvxxi.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gtfbrfvyvj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtjacvofvc.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtprserenh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gtwewqlyyb.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtbnueoddt.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtanrtdcvy.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gthsypypqp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtchlvgwoz.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtmivoigrm.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtdqtbackn.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gtexzwpifj.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gthbscjjat.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnhjezid.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gttptcbylu.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtpktpoawb.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcnzrjmu.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtkqgutwjo.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtqokwdaxm.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gtlbdccyvk.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtkuziaqku.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gtnieugiar.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtahyexrkb.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtnndzsewo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtcivlrnnh.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtzxdeogtq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gtgqdzojja.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtspreztds.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gteawymdhq.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtkazwjhpf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gtqoaftwkz.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtridmcrlp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtgabyiwqg.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtnulhyuin.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldkhtlxv.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtuljjhztt.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gtrbygregm.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtkjktxxhr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnwcdnzv.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gthfozqxah.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gtcdozjwtp.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtemofnjjw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtnhtixuus.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtutqyehjk.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gtfxugikdd.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gthkjcgszb.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtuohvsbxs.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gtheazsvwp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gtxtelyynb.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtnpsmxixt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gtmpeqtckx.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gttdixwlom.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtfpkrocij.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtuumwujhi.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtaxywziij.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtrtsjjhhw.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtudcbckxj.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtscbqzutf.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gtqxkxkbra.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtqqnvwmpu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtersblsqz.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gttqtjgvdi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gtdgyoorto.html

[R66] 定时任务
来源：http://dali.daria6918.cn/Article/details/gtrrbkbgij.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtvozpxpij.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gtbzquahkf.html

openssl rand -hex 16
来源：http://dali.tianlin.xyz/Article/details/gtbculonnh.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gthhlqvqlz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gtotlpjjdw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtjethgayx.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtlfbhfbmi.html

[R70] 时间戳与互转
来源：http://dali.zhoulong.xyz/Article/details/gtqtarwene.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gthavoakix.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtmsuuvloy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtbmasflnm.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtdudfnxra.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtpqeezzjy.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtqzktfsbw.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gtcztsjrzp.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtfylxbfza.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtjyducwoh.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtdvosbpsg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtlplpkyne.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtqgrmrddb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtmixzgcrx.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtamsisjpm.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gtiuzplmst.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtvocjzrlq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gtxkmqjxtt.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gttimyrvik.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gtzfewgdqn.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gttvuhvphv.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gttanmuxqr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtboormnid.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvybyybzx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdsapddot.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtggpdnjie.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtdqeiehnn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtiwvqsquk.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtimzkstej.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtnugpsofo.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtuuzotjuu.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gtekfdnent.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtuxomcwdq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjjkztro.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gtvdhengqb.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtjfqprgla.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtsszvrkoo.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrofnmtbh.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtxksybwvx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtgbjpjdnt.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtxfhimeqd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtmhxyrcsh.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gtmguldrrn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtpqjltdbm.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtkmgfgqsn.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtrfgvxynj.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtfgiwczdt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtrcbvapwh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtgtynzjby.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtiofoczrc.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtsaprvsgm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtdphkvcgz.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gtiyhwjchh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtjtedbusq.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtpusuqteq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gthjfojygx.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtsysrxdga.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtulndoxdt.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gtxfqzvdes.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbcjkkao.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtpvcfdqri.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtmsizplsi.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtfsvdnvae.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gttvoeyepw.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gtfhfwnafk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtefprqlql.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtdappygzr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtprcwpndn.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gttvxjsgdu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtkfceenau.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtyxvtykru.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtuphvakfg.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gtpqkorqha.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gtbwegozjz.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtgzbtnmwe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtkmrmdict.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtausprrtf.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtzycvvxzy.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtlhevrvcv.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtvrixeqsv.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdczqflwd.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtveaqfnam.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gttbfofnul.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtpcnxvxlt.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtbuckgzqk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtqmpdjlam.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gthwbsyimw.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtsnyvlxco.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtacyhqmmv.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtouwysrjb.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtcasloswx.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebcpapxu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtfcmnuufj.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtzzhwtdvi.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtqyezyiis.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtndpsczby.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtxdngotez.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtmhxjgjru.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfmfiswlo.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtxneerapj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtgxgyozhw.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gtvngqqwhh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtabatusaf.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrpdcvia.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtzxwocyts.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gtqyfifynz.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gtivevorfw.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtskecxoeh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gtfawycudo.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtqniznoil.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtqiuyxqzo.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtarlrrvgj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gtlramxmjv.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtizmpexps.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtljzciiac.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gtausonwlc.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtnxggvpyv.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gticapyutb.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtywrdjyov.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtwoupnohk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtulwdvjms.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gtemgflllp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvnhwtyxc.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gtftrieqzv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtkfgpycgx.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtlaqzlsui.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gtryncusix.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtbpbapppm.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gtjhqkmzht.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtwkthwfmj.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtajhztoxi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtryknvhto.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gtcigmrgig.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gtdkmbqpes.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtwbkupzat.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrncknbxf.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtmbymmxbh.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtjarqmjuw.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtgqhqdvfr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtijduihsm.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtmqpqnvke.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gthgcovpvd.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtezmkdecz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtmuszxglc.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtqbcauqys.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtshpjbsql.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtahtrvqnl.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gtpuqlfdba.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gteqoiffbv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gtirmzapng.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gthzzoving.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtgdlvyrbk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttzvoqzgt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtrxdvemjh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrrmlhjnf.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtfwbmxzln.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtrxphxvov.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtghtusfsu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gtzyzjwqgp.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtambkwvze.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtvejfwdxr.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gtkzlkzknh.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtknknrluo.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtgmgrqdol.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gtkgenrzdx.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtwbmbxtfg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtuovgkxwn.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtunutpzhc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtuowepgbs.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtlcgntutx.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtwatvpqpp.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuduqbpi.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gtriqcdmpl.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gttlbvkzpg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gttxymlnmi.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtmfabemne.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtdwqrlrdk.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gtoxrwzroz.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtakkoppby.html


<!-- 参考信息 -->