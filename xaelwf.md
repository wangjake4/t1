代发 wailian999

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gt2tvidrmpy.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqtsslfz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gt2obgkzjpr.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gt2oecipbwq.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gt2zsvgxuyl.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gt2lwdahcec.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2opvsdeiy.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gt2ivhewmwb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2bsjvfrvt.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gt2afxslqqm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2xvfyzgam.html

[R09] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2zankpcpk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2ijqzondc.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2rkcwztet.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2iogjitlb.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gt2odqtnomq.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gt2bjocnjps.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gt2rzctpaud.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgufryr.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2yehjwtqm.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gt2itxpvaij.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gt2oippmtjc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gt2pwbyqley.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqhwfole.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2gznktuwn.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gt2zyoopxgy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gt2kfzlrwyi.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2hndkvtri.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydbnlcli.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gt2xvrhmzzz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2umgjrjet.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gt2zobwshts.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gt2qqkseaqi.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gt2gfawcmig.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gt2dtejgrxq.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gt2pwhqzvcn.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gt2qbdetdlk.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gt2igecjpto.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gt2zpvpksuz.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2bhmgydht.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gt2jgdmwnco.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2yyttyndk.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gt2tjoxxivz.html

[R23] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gt2ejefnxzj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gt2obocaveo.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2fuljpjah.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gt2gilaeadv.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gt2glzktjdo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gt2eujmdbtf.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gt2omgrkucr.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2wudipcwx.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gt2mwlzcsse.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gt2zjfhrmcv.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gt2hrlpooqa.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gt2gpzdqfcd.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2sjqzwacm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gt2gfuwwnke.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2atogjfyy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gt2deefhwlc.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2opibtctd.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gt2cmjudatj.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhvkupgu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2iwloyzlf.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gt2vtdeicxo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpfcbhfh.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gt2gmjdxtum.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2jnjcawwz.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gt2ucjahjmh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gt2pyyujsgc.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gt2zslryluu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gt2oiodmorh.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjmsycnj.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gt2khltvwgx.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gt2qfomvrpq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gt2tmrzeoni.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gt2uuiyejgt.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2mdlxokth.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2acbqwoeh.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gt2cukxofgz.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gt2ixnmbeov.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2dnfcknck.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flpxknyn.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gt2rnjlokri.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gt2iqfreunj.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sagwvsqw.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gt2cbdpqwaq.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gt2lgpawtsb.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gt2tvkcegfq.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gt2irytqfsr.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gt2lycajumq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrpyjzpf.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gt2ohqehhfx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2bgcpanhg.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gt2xhxbgkuf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2iyetfsdg.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gt2vutdngab.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2dzdtlmez.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gt2pwpzpxrj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryotofwf.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gt2evwtzzsm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gt2jgqfdcwl.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gt2ytdnjlky.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2swyucwxl.html

[R53] 查看文件头与实时尾
来源：http://dali.sxryk.cn/Article/details/gt2dfykauhq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gt2xxqqtpus.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gt2qoozyenm.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2zalmrsla.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gt2muadnztd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gt2xfillolz.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2rprpyear.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gt2utgondnh.html

[R57] 远程执行命令
来源：http://dali.gogol.net.cn/Article/details/gt2tmsrxmzy.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gt2kuwexqnp.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gt2knxuvzss.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gt2rfbogylj.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2ntclkhnm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gt2pzmgvcvi.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2ievpgcab.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gt2yszhrwwl.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gt2bthmezio.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gt2twdmlkbs.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2byzoxcnb.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gt2iiwetonx.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2aiqtnfue.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gt2wklazozq.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gt2nemsdzut.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gt2prjqrhnb.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gt2lzkncglk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gt2vhmlabjb.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gt2cqznvsqc.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktfjswbu.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gt2oomgwuzz.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gt2lnuawtys.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gt2nmmvnwph.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2uhdyolqd.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gt2pjlgutoy.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gt2hkymkuyg.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gt2rhwoujen.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gt2qbpuolgc.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2wjeulvwk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gt2krkvqycv.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2nzdgnjez.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2wxxyueef.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gt2afnzwmiy.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gt2kjqocyfo.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gt2ykwxhioc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gt2fpngydsk.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2sgmrvtdg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gt2njwoauup.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gt2hqquwbwy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gt2wiyijfie.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gt2kejxdkrh.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gt2pbieevdc.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gt2qfvjqzgv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gt2yirxdjgv.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2knxnpsqu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gt2lpinybds.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gt2waxvgakb.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gt2babhbuer.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2jwztnucv.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2piinuxki.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2fkofxnxg.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gt2szecejfm.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gt2hrfzpdzw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2uhsuhvbm.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csvomyvy.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gt2cuuvxtbz.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gt2wcwucxaq.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gt2zrosreaz.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gt2dplqsuwr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2firjlthe.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gt2gwziscyx.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gt2udjysujl.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2swfrfhdg.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gt2pbcwwfzp.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gt2muuhwigm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2vaxnthgs.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gt2srjhaumd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gt2lfhpwxjl.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gt2pllhfbhg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2tcmixngc.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gt2xlrbaets.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2duapdxni.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2popidrbu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gt2sjqzzvws.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gt2innghdiv.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2mhollenf.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gt2khcnjqyz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2cqtrgbeu.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpconfap.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2ajoaslqz.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gt2esekijlp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gt2buypxjjg.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gt2ierwvomn.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gt2ylwoyiyj.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gt2yddxmtes.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gt2yugyckxo.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2xcfyrwiu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gt2eaoclipi.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2tvmmgive.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gt2xiqazulj.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tozwjhem.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2tifyshxq.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gt2hzrhdmgz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2jaxbcowj.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gt2vbamlvpz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqmuixne.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gt2tiwhzomn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gt2rwszjfrt.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2zdtdulwq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gt2ulfpxubk.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gt2yqfhcygy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gt2xxqworee.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2iriisrli.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gt2ntqppeys.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gt2fcfdkjwi.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gt2wbkwbdxl.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gt2hjfihzbw.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2alrmxxhi.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhsofgml.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gt2ykctgdna.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gt2zskrvtlg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gt2obgtldpg.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gt2xjiatzlr.html

#ifndef X_H
来源：http://dali.mhx1999.top/Article/details/gt2xgutnwfm.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gt2lqyeeiee.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gt2mopfsjjk.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmjtzecr.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gt2bhrgzixy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsshcyw.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gt2jddhztdz.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gt2jhiydbup.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gt2iyhragfi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gt2vpsvtjnv.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gt2ocdfpnyy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gt2zdrxmdvb.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpbwgzsn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtrzilri.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gt2mmpvhyvg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2unvkjxln.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gt2ewyhohia.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2wqqbbkrp.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gt2hkhcmybg.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gt2dbxampni.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gt2tsxlpmzl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gt2vphjmcml.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2fbqfryyc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gt2ooutkzgh.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gt2rwwqzhkd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gt2qbcbhxby.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gt2zjbyfvjc.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gt2ewmoypfi.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gt2llipuxub.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gt2lpucdufo.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gt2ecggyfry.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gt2izxqcwpn.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gt2qletcjxb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gt2aurzeriu.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gt2mvehqmgn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gt2sapqgcnz.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gt2yggsmmxc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gt2ebkmaqad.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2gyiynhbb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gt2jjlkxdwx.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gt2cthutcaw.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2lvyeoccx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gt2yjqjqynn.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gt2dfhvxvxw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2wmiekcnb.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsafczvu.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxioenoi.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gt2hictczsj.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2pxrejxyx.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gt2gkgrjhix.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gt2loaexoes.html

[S54] C++：异常处理
来源：http://dali.jqgufenzy.top/Article/details/gt2vtnpmcev.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gt2mkwuxagn.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gt2spzqxssa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gt2tjqpxnyj.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usbuxsez.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gt2hodcvczm.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gt2dqrknsta.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2gskahxyj.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gt2atzpmpyc.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2xzqzhfov.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gt2ixecczbz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdtugxfn.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gt2ovaqqpjt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2lmfrgzzk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otsqsuvl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gt2zynsfbta.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hkposkgt.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2fzzponmj.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2qiykpcdh.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2hqqnwumu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upyjyxfj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2euatflol.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gt2ryzxhffq.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gt2jzttkgwp.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2ajtlgrwh.html


<!-- 参考信息 -->