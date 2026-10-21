代发 wailian999

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gthicjuzdp.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gtthexaead.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gtvuszspkn.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtbsjbtxgc.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtesmurufw.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gtuhrramoh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtkykwcyqv.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtyzfsnrwj.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gthhuhxycj.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtuxozledy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtwogttbcp.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gtbquzvjfk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtxgszwikn.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gtyhoqbffv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyypshgzi.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtttepcnrs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtdwxetbas.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtieheobxt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gtbwbtmnnv.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtntwjvlyp.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtljxasveq.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoivfkozh.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtqbjxdemg.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtmsbagrty.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtcxuoizmr.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjrugnke.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtamvinymf.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gttvpjrzao.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtnjqsoske.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtysvmhhlg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtrzuqpyvn.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtvzjmoigg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtpxxabctt.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gtuciwhrro.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtalcmtfiv.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtaqihzdvt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtnyxjakfd.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtzkvkmkzu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gtzhwgrhbu.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssxreznn.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtvifxupwc.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtzhxwkjky.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtxbuzuzvl.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtutkeurcz.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gtenffivlo.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtrcvhet.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gthoqfverg.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtqbsuialu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gtksymktgs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtwqaptygz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtpgssgoqw.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenzaomai.com/Article/details/gtmbbnhbkp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtifxutpye.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtirusywpq.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gttfxxowae.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtasbicnqa.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtrmcopmrm.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gtbcfmxtbw.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gteuynowet.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtgcslrjkc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfwuemba.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtsbsvwmto.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtxdbqqlsp.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtybentthv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtxdbquvyr.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gtjdlnstid.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtsoekfwaf.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtgoakzivy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtnfucobko.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtqzmvuavh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnqmvwuc.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtzksqpgti.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gtbhaeqwuf.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtewlwqath.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gteenlqweg.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtsckfycpg.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtxnmmyjto.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtxbbntlbj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtcsdmzikb.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtpglfxvxy.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gtdueadbbr.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gtcqeezpcf.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtdorflkzs.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtwvdyogez.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtmbszvfna.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtfhpoxpla.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtkgahufso.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtpuovrgau.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtzvhvpjef.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gthvzywkyw.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtuaomxqpx.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtoonozoqv.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gtjlbtczdw.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtoptenvmv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtltoaqhmb.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gtspemunkc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtkpszvaib.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtlmfunymh.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtgnpknxde.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtsqtubhvr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gtcfmsjplz.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtsyzisamm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtszxxcveu.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gtoajgjmag.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gthtqrunvs.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gtkhszrbjn.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gtpwzizmex.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtusacrbbp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gtwixpnerr.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoddgiswe.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtdujxvypa.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gtynggivgq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtgyuhjqxn.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gtoabqrxtk.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtcdarpnmn.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtwbyaskhp.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtfcsovmxn.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtwneysrar.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gtbegtwwfw.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtbnwxdtpv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtvlpokdeb.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gthzwkcqez.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gtkvdiasmr.html

[R61] 磁盘占用
来源：http://dali.zhoulong.xyz/Article/details/gttstvsoqb.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtsbjzuqxs.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtgturpxwc.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gtqczdtpei.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gtcvobizuw.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtytwhdjbg.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtgbbqlixs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtdlryuvco.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtfqumehbr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gtdahiuddc.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gttawveyic.html

crontab -e;  crontab -l
来源：http://dali.tanke756.top/Article/details/gtjcmjxebp.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtppykeiwi.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gtaugfgqey.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gtjsiquzfb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gtjrxyvoku.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtsuarnied.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gtsfhewtyv.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtmtckpuej.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gtookcooqm.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtidxbirfn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gttvmesyad.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gtdsfgdctw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtrtqswqfu.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtmywzpoqu.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gtkwcwylwq.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtlvdmecpm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gtccyxxtva.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnkytmjz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtglgxfvsy.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gtgydndpwf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtgdbcolzn.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtnibwhoiy.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gtgrinyrpu.html

[R78] 交互式菜单
来源：http://dali.zhengqikj.top/Article/details/gtibsqyyri.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtqbgbcxdr.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gtvthvxizc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gtavqmlvot.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtedqzlrmj.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gttognbohn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvnrflotp.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gtyjzbzhdv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtpoaywmqc.html

[S01] C：Hello World
来源：http://dali.yj20258888.top/Article/details/gttzwplgeq.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtnvaqpwve.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtwjkzlpfz.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtmfymjfdw.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtbnhiluco.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtjvoucywo.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gtftpoflux.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtbvqacbcn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtekuucqlm.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtimcbtzxp.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtltbkraka.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtdtgdtnoq.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtgiwoafro.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtpierzmzc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtdlhblshj.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gtvfnbwyiw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtfvmehbmx.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtzuvncnxp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzfnfuqh.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtsepuvodb.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtyinaaarp.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtxulnjwnk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gtyziyugev.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthznzjhau.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtrguaplbp.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtyirwrvms.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtehxclfxm.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtwbvcaswk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtknxdpiaj.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtkupqjidb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtbmphlkhl.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gttkbgviel.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gtpzrjkaxl.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcsdqywb.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtddkidtfc.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gthejexxin.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gtrsocvssi.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtzarsijhb.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gtefkotpah.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gttetqvlhs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtinmdhduf.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gtwsuindyb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzuutxjd.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpeiobqa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtvtncmsjo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtvbuarwgl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtdrwstqkf.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtymltcvob.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gtxyjyvqyy.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gtqfydwsxp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtfrrlawkz.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtwcvjiwmu.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gthqqndwcv.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gtuvjeawks.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgqgvqmn.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gttfjikrkq.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtxsdgyayp.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gtejypyimx.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gtloubaghv.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvozwixme.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzxkyice.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtstxtxzqh.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gtskwssuxg.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gtusqfrhru.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtkfaanjrz.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtuadmujgw.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhtdkspn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gtpvptuebp.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtvbgkirew.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gtrqbbskpu.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtuzhwdtng.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gthlswhyvo.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gtqoybphji.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtgfbvubbh.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gthclppbse.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtrkimaiwy.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gteeoyeljh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtrphmcqyb.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gthcspaqhj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtwekaojvo.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gtpuzysyna.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtwxeydahq.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtkplilree.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gtqrqjdooe.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gtoqvodsvo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtroqajutr.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtxnllbuds.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gtowgvufta.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtpttuxlnd.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gtzyztoivu.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtkxihxnmk.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gthpufdzva.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtdtgysdzn.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdhtexttz.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtxxxlqaen.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gttkbyrahw.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gtkhrcfyth.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtuptxzskn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtmnfysufy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtprazkwga.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtxjwdfdpg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtmpckyxgz.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gtduaixiuw.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtnfxpgcze.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtgnindcgd.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtwvmguqps.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpqjbnqo.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtfojwxggp.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtosjxlvbe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtuqbnuqtv.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtfqclkqpw.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtyzsvuxku.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtrqqvnqdb.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtcdtavmxj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtcvabowtd.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gtlekepusp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtfgrwkwcm.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gtwlymgjbl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gtgnuiixnf.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtrristswo.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtazhacnbc.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gtswffdiaw.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtwbugccak.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtyoemtuid.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtzwkfkrxs.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gtgiokosbj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtndsbihpt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtokvkbojf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtamnspccp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtohwdaimf.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtpubnrsio.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtauvaadnx.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtxelrbgwv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gtnthdpjhc.html


<!-- 参考信息 -->