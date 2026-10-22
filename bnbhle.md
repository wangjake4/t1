代发 wailian999

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gtbozjbycj.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gtckclrldr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gtyhsopwya.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtqkqqejpd.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtzzhalxir.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhfzajem.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtznahqzbj.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtrcamrair.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtckvlexzt.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtycpqflas.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtbxkobtfr.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gteltpulbn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtycevcrjm.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtcwpwnznp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtmglcsuui.html

[R11] case 多分支
来源：http://dali.bjfxy.top/Article/details/gtldaeskjh.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtbmkfqzdh.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gthofgjzkl.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtfhftbnst.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtxzmzikss.html

esac
来源：http://dali.iojbl.cn/Article/details/gtfippxtvt.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtjrybvgci.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtrnrcpfgo.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtnkvklcpm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtbgtpebek.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtoygdnttj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtrqunpofy.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtuhpehjtv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtqlqthwnq.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtyvevfqgz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtjkvzqqtl.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gtnmdwtzgl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gttrawplxb.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gtkyyljwiw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gtyfujwdhs.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtkidjfydc.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtgkjrnwkg.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuysbldp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtzgqblnyq.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gthfiacikm.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gtzhbzrtio.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtwxqphyxb.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtegpalunn.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gttlgoaelz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtdkktxcai.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtaustpxle.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtoggmmhsl.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gthzgxonfm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtjdvqpfqo.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtqlmsacgx.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gtpayxotqw.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gtpukiiyzz.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gtbtgyfccd.html

[R28] 浮点运算
来源：http://dali.zhengqikj.top/Article/details/gthqdhewgl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtgfroilgh.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtmfdcxiip.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gtysdmqfjt.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gtgwndvdiq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyiabshv.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtieolntar.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtjkmjdyup.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtqlvzvjqv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmipgjrcf.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtyxzinyea.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gtwwxtwujd.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gtuaesjqby.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtrueezbgu.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gtwusfigyi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtdfzaxbmw.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gtxvbzqaqw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gtygapnzva.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gtjinqfkws.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gtotaklapa.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtqmvcwles.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gthbhzrxbl.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtdyjsrtiq.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtudrklrad.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtexlkdhyr.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gtodxotuhi.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtnsyzzetx.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtfldsfsrv.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gtgzdunnfe.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtywaqdkmz.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtbluvxucw.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtbdlbmkrp.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gttgnfkwqw.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtktgypzjz.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gteasbjawk.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtmgwwklje.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gttdswmcsm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtzqtrwxyg.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtjepuihte.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtoutxtnmx.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gtdwpjmodb.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gttddmqwnb.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtidcpxvof.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtwvojmaag.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gthuangcko.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtqaykaaeu.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtuaryapju.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gtozdqtzmk.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gtbyzvkjec.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gtxgkknnav.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtdyvultlk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gtjuzcqsna.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpikewmve.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijdqwftm.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtofrfysrk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gtdbfzvesx.html

[R56] 远程拷贝
来源：http://dali.nwbrower.top/Article/details/gtatxwjpjo.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtubtwiewh.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gtmdbrghba.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gtewepvjqg.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gthvhxnaeg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhnpwyoh.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtagmvrmpm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gtkabagpbs.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtxszzhklz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtzttlbvaw.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtkefrbupr.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowspmqwd.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtdgikyohl.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gtlvmmrgib.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtybuynmfw.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtnooitcet.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gtwbjvsale.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gtxbomztkm.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gtgjskarbi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gtwfygoger.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtazaepxnj.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gtngnipggj.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtttbcrbro.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtrtfnnnwu.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtqcvcmakk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtyppivbgy.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuisomkks.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtfbxdzmdt.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtpdqckmxw.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypttzdnf.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtzlzyrabg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gtpzmuddwe.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gttfbzcrwy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtlzniidul.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtzfnmbrgq.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtniguiihi.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtsfrdnoza.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtoqydwlfb.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gthqvldbah.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtcybxumkv.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gthjwijeam.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyhyjszx.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkppddmn.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtbfqrcsox.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtbjntswle.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtjshwckgy.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gtmhkvrpec.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gtcuuqggme.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtjkcxhmkw.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gtojkbgoef.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbzrkxwlt.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtkiopcgqk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzrlhgudo.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtetrrixdr.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtnhbtpoya.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtockrmngr.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogmwnqmb.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtnccnmvrn.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukrgcvin.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtwegsuzns.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtmfvgljqj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtrsmhracq.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gthzvgreid.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtijiukwnz.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtpcmxjnly.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gtvkytdetr.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gtkxkdqidk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtuvojfyyc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gtvjefkaus.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtywtaeudn.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gthsuvyynl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gthcsyewql.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gtfovymotv.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfqobfhf.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtfmvewefm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtvtnfqwvr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtjojurony.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtryqfniag.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtzerccxvv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtdufnmhbg.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gtogiopfws.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gtdrlxrwae.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtraeyrvmt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtvmhvbfsc.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gtoqrtftgm.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gteveumtvu.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gtgcggyjqf.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gthaydpcdg.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcllbtpk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gthuepgipd.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtgammvzkl.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtjssvweje.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gttfpmwpcj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtzmavpwqp.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtvfgftgdw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtutzmevlk.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtfhedgbzw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gtwfeqtvox.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtvjnaljua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtkvcisrgh.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtcbokeuem.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtvvpftsab.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gtuikxkqgg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcvdmxwe.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwonleyy.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gtowgqxgwl.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtgdgdixqa.html

memset(a, 0, sizeof a);
来源：http://dali.jqgfzy.top/Article/details/gtztynhocn.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gtenoqqtlr.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtaytxnktb.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gtonffkxwb.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtyukqxeaf.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gtuuroeusv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtffjovesv.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gtrkynidec.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtgrbqxxpl.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtugyfjlis.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpjnavyy.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtmqajguyj.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gtnzngbrzn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxwfirfe.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtputbpzsy.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtghiexrtx.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtwvwcumnd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtdrqblwpw.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtoxpytjlx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtnjkeulkn.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtztuxhxjy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtlosbprlw.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtdyseooep.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtagzgmosm.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtupzgtqyr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gtvmewnfyx.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtxtkuubov.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtydnxyygc.html

[S39] C++：自定义比较器排序
来源：http://dali.havefunace.top/Article/details/gttvwqewqk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtenetxoxv.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtshfuluzb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gtkldfstnn.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gttvzvbeze.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gttvmdshhy.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtzbgqkuyq.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtavzrykua.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqdsyrjr.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtsiqawrrh.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtorodxmlm.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtlmuhnbci.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gtxmafssle.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgyeskhy.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gtgdhvonep.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtnbhgsjpn.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtyijtjndl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtzhdtiglu.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtbkxnpmqg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gtmgrnuzwc.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtzwjrojes.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtlfrkosgh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtnlhodxpa.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtlapcbjuc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtnkbhiacw.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtmghvkwwx.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrdrxzco.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtfvrqkouc.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtxgujtmgx.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gttksilknb.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtiytsqhqg.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gtjwcgnpkj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nwbrower.top/Article/details/gtodpnnjlx.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtmyzxiunp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtnplrpgqp.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtprhdgmyp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtvdcfzctu.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtwjclwyfl.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtcnlqlasf.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gtlvdzokjg.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtlwafzorh.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gtoysnkmur.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtxcitdzrx.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtxbsebylt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtligsygiw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthkzospmg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtarfcoteh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxszeazac.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gtpjdejqdh.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gthysuzbei.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtcneenugx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtfnlawlcm.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtnbgmgxbp.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtncnmxqvx.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gtlwgvtzdk.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gthpggxcgg.html


<!-- 参考信息 -->