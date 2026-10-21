代发 wailian999

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gtcuowrhld.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtigqnzuqu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gtjmhyonyi.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtjulcoiwr.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtfvztkgos.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtvkdilyvs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyndepjcj.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtgxzyntfq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtxnrckblk.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gtantenfcu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gtiuaxcdak.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiftlaru.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gthdfjnfck.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gtevkhkltb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtbgcecijt.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gthizhvotp.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtmizjcqjc.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtpgewpprz.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gtkfmqprpk.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gtiuzxaniq.html

esac
来源：http://dali.guowangkeji.top/Article/details/gtnrqzhbuc.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtnxlxmuzr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gtqxtgitfg.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gtnvufcfos.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtulljvzzt.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gtcsinwkcz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtqvdcenig.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtvfqnulqi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtvjjzmtwq.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtwejplkax.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtzcyioyce.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtulegdxwa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtgsmeguey.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtceaszaxf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtryrrrewe.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkweyttq.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gtzvtladfm.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gttnbuszva.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtojpaikkd.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtlpobgyus.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtqnledtuw.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtjlgkwfst.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtdijedqpw.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtykjsucsl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtfsioftzj.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpttqzsxa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gtozfoxecq.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gtjrkucztn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtuueownup.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtjjbvuked.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gtcvghgnrd.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtvdzfukvb.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gtaaeupvio.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtjhfulpsp.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtfkeijoeo.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtapywmite.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gtmdgoomys.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfgypwzr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gtcgdbkjlu.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gtgsbnfxlp.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtbxehhbij.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtssggvgkh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtalfduhtu.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfwwiyqj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gtzosjddsr.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtklrmuekm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtnlqpnotp.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtqgaycuwh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gtzwsqbfam.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gtsngvjdxy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtjcfnkwyn.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtecgvqamg.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtezvatscz.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gtzxohrjof.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gtqheseogy.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtqibfkhbj.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgzeakbi.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gttgezqkhe.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtjojnecpb.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtxgbcykha.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gtcfpjkkgj.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gtopnzykzf.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gthrflchmr.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtcjnlyend.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtzzxqkgle.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gtlldtasvq.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gtffisqudn.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gtvvzunwmi.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtlmgnleqz.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtcectgujj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gtfbgcjklz.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtlwhejswf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtiwshiqlj.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gtscduoytb.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gticypnfmk.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gtjcgbukeu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtryhepwzi.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtggeaffci.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtvpegtjvv.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gteguuacyy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gtxsrzvcho.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gtmwenicqb.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gtyvkiaily.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtyvazddpk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtgrfnojos.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtlvjyeglg.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtmahnbrdz.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtxhlessqz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gttzwvsmkl.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtbbmynqkc.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gtovjwegzq.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gtnyokcprn.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gtuohjejgm.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gthyagpgqz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtbcpimrnv.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gttdgkozag.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtstklaksx.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtdzdmfqza.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gtmqqfunfx.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtuajaomey.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtjlpqneqp.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtemyyhyws.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gtbzlqunwc.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gtgjedghvr.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtspactphw.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtrkqqghxa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtdmypnwna.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gtovsbbxvg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpqmtsrq.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gttwtevjdm.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtywhdvhfl.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtmpiotuqm.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gteczcbpqm.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gtukhbjlvo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtjxileyar.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtbwhayjmc.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gtbslqfufg.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtlbwwfdad.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gttuiqdteb.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtygyfceqf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtvmcxetxp.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gtvgospthm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxybyszy.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gttfrychgf.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtvqtdrrqw.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbzqsiyj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtcnayqbvx.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gtputskbqm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtgpoiqwak.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gtduoznhhh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtfesevqsn.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtcmmapcen.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtsrppcnzx.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtmskhnxys.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtezlzerip.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtsfmyfdza.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtutxzwnou.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtfpiamdkr.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjcrdvbc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqjqosqdl.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtbznlueft.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbiadcgcr.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtdtuxzyto.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gtdtovqkas.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtxycawcyb.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtnsdhndfp.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtiuerkcpm.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtrlkyzzek.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtsrdfkvxs.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtfmlqlruz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gthtnpjlkg.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtaprzxabb.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtzelvsbpl.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gtmugugiaf.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtlvapwrso.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gtnyxzqzbx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtnzswjpnk.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtmiwcaugi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtscbmqwhj.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gttxcigure.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtqebijgqr.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtkfpsxcjq.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtrhxehwxa.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtnemhnrsm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gtmxnftajr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihgbrnld.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtjnspcjpx.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gttpifxpgo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gttxjwjwpn.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtpfecusdv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtsiqowgdp.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gtzdvjiayl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gttavnvzvi.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtleuddugr.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gtitlkoykh.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtimcxtkuc.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtakclwfbt.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtyqvajfyk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtydccsftk.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtziuillwm.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtiecoihse.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzamltcah.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtqajhhwhr.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtdpsjowrt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtyahwsbpz.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtneuijxsf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtqebipzkb.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtosgiggwo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gthnsjtbll.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtbmbktmzu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtmkbxjnrn.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtsaqbzool.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtyqkbeqfx.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtkzdqzsoe.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gtpsdqqmhm.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtjupxrumv.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtqaabfdak.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtbxrzbohy.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnaxufyrq.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gtqhbnyhcr.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtbnuvdznb.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtnolgetxp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtyxknrihr.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtbukqpvib.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gtfxzjqxja.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqnrovid.html

#endif
来源：http://dali.cheryme.top/Article/details/gtkwiolkyd.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtxqhnmvbx.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtuvfdxyre.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqjaexbk.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gtanwmtzku.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gtmmflsiyo.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gtkivjfqzr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkfzvkoe.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtyeiyernx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gtjoolwfcw.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtifkqsdsh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtjmjhhuaw.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtfrbuvdwg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtwrsrbthu.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtlrycdxwd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gtwwexrgzc.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gteanwiluh.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gtkzmgiqcj.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtrywjfeqk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtermykhjo.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtmatgxrcb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtteumtfkk.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipkokjjf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtjpvjdniq.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtoaudoiqb.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtzfomwwma.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtcoznvahr.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtzdidifev.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtymandqpp.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtlsmageau.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtjymnhvdj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtqrotttbr.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gtevomitcv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gtueeuynxw.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtvdcorbed.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtlahiayki.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtmsnwfadz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gtzozleuti.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtkfoihvos.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtmgelrsip.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtusorplwd.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gtyxgyffef.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtxltretcp.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gtdndfhmsi.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtyfgxpasj.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtcjlndrlj.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gtanfrdyjy.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwtknugf.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlezycehv.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtgnknhelk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtsugcwkqv.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtllemhqnf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiaufatao.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtcscheilk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtuksjzuej.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorkqhzix.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtphifxfnp.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtzrzstqhk.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtkvbnuzsy.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gthuzaidtr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtbkxcemai.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtreamopqx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtzhrmpusu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyksgzsmr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtnlmfsswb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtluatepxw.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtrqxppzpw.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtksnahwwd.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gtqdqptrbu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gtecvmbpce.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gthhfflpcj.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtyxqhdfgj.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtmikqsuiq.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gtcoiehgfe.html


<!-- 参考信息 -->