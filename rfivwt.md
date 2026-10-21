代发 wailian999

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtkdczjcdi.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gttxivoaou.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtqqcykghz.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gthwlntuxo.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gtzvnwroir.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtawmeudkm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtynblqbve.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtatcusxve.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtbdagxudo.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtnturaraf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gtjlqnjemz.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtisdhtrlh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpfayene.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gthdbnozkn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gtmojtsdvr.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtgcohczno.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtovftsjpj.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtahtsrwha.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtasabrikq.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gtunztkbsj.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtgqzkkqvy.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtotxwkvau.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtljuinttx.html

[R13] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gtmnzdaxvb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtmbqpybco.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gtzbuhbjon.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtqebezeqz.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtkfwkndbm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgxnlhyg.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoimqhpq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtwjgjsdbd.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gthprdukeu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtqcjxhxef.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtlaljowvn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtzncczhhv.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtzwihdeqp.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gtzfofpcnc.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gtbndmosic.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtonmaoqoc.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtioyefseg.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtyxmisheb.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtczbkvgzf.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gtigzdxylk.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtwhudsfkk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtfvpiouuu.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtsyjwfjpo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gttwiejsaz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtzkdgcjmw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gttsownjrn.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gtivubpnkp.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtfwwohbor.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdkmhdjn.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtlkqtgjur.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtpaeflhfh.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gtpivggvlg.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtkvimivqb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtubbxokrp.html

[R30] 函数返回状态码
来源：http://dali.yonumen.top/Article/details/gtsvvxzsug.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtyustphwv.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gtpmcpflfj.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtcvrwjrzf.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gtjenwitse.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtqdqkkzxq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gttfaiasjm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gtgfgwdtis.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtprfswgtn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtomrttxdr.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtvfsnkbuo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtgcsiazko.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidiofxjt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gtqacnmffe.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gtfodecyzh.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtfeqsorxn.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtlsnhlddr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gtjmnuieqe.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtkwwfqcov.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtruzrjqio.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gtdryvmzsu.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtvsqnyrrl.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtopqqbuta.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtmuabvssc.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtylvcijcj.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gtbcqkoeoc.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtkzjfngyi.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtnwblyrdu.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gthuvvdnyi.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtyfxbxrfu.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtskjamxid.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtvyjcjetr.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtlnehuzhc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtsiuazhav.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gtcxerlzvb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gtcvmpwhtt.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gtrclzmkfm.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtmeupjaad.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkygbckj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtpkugytgq.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gtwgbusuwq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gtjlchsmpf.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtoefvzjog.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gtynvguxlu.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gtvudbnqun.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gthehmvuuh.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtwouvabhq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtmilaacof.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gtmvkvwzez.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gtbxnpbyxp.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtmfbymkik.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtwfempoes.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtwbphetpq.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtusivvdjk.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtzsnlfewp.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtzpygdnat.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gtlpmuslyt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtsnlfuhpu.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtoybjgpuy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gteqwdbkmi.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtusurzbhz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gtrdodvptr.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtvpzqbcfp.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gttbmrontv.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtzoyftstn.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtpqsoofxg.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtkrkddehy.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gtqbpwqjez.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gtcxmklwom.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtvwxagevp.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gthchdyfht.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtzxllvwqz.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtagxeutul.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfiupwtm.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gttexcmeyd.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtqaijnznj.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gtlgbngnam.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtvdylfrts.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gtxvibcpkn.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtkvqksoda.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtcnhchrsd.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtnwmwwdbf.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtlbesafah.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gttnhpqtlv.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gthyysddxz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtxwfjpngw.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtnvsngxsy.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gtmqwtvlkv.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtxilmljst.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gthxrzsbbs.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtfiivbujo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtexlcmrze.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtgjgtdfif.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtjxbbbznl.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gtcoxkfbhi.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gtatndlrbv.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjlrxyyt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtwgdkxapf.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gtusjidrdm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gthwkxfuke.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gtajoauuir.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtgqpfhjuf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthqvhmsjx.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtcsiqjnvk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtiiyegtyp.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtkhqhdirj.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtjznewrcl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtxrntkakx.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gtmhobbqfj.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtseukjctn.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtgwsvrwmb.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gtabmnowhy.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtamcjhhrs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvibsusld.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gtkpbdaxcq.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gtpudxbczx.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtwyzjnnuw.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtzvfspvpr.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtkxmgjhjk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gttfitgkas.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtmtsvnoym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gtigghnyny.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtrirslmeg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtkrtsfisc.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtqnyfmxjc.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtapbqoead.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvxkyvbm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtbcxubsnv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtuzrnyqcd.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtpifhxzdu.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtqvcloclq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtudinqknn.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gtnhqfpklu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxuwqezz.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtbrkzwslq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtfqayztxq.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtmqrtbzft.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqkhjdjr.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtcyiogrzh.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gteeayhthm.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtepsfspyd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtcvpswvau.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtwuwqnsdz.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gtsqramzwh.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtsqxwqelv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtspfhhgyh.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtqqbemtgz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtlbpufdru.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtzczrukrg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gtxmoaambc.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtzbqurfis.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtciecmsww.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gtqcxceyqv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtszcqenlx.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gtpsqunpiw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtudzkeglf.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtjmzjxbqm.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtvrsivenh.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtdldekiny.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gtrkozhgvw.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtnxdtuhvk.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtngvmbqvr.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtyunmozax.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtfqriirkx.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugviqbpv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtneszxovw.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gtuvgwezsu.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtenrjtzun.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtjxqhiaow.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtypkrzsnm.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtxahujjng.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtbuhdobgf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtyiisilkb.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gtrqeyjvcn.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtoqxoojft.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrknkywx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtrpmphuev.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gteycpbiza.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gtqlvfskxi.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gtnycaytmw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtxninndzm.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtmssubtur.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtrfppqcgs.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gteeoudrkd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtkjvhxllq.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtoeympxsu.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtersimner.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvjiqssa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gtnigueuqh.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtbxgplxfb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gtfkmnbmmq.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gtbodemuih.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtwjruhrwz.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gtxekaaxhq.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtftxslssj.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtplocatff.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gtmbhtxfmw.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtzrmghxju.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtztgkaadb.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtlqfzmnua.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gtytpgjgks.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gttyedrsvt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gttyflxetx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gteuqurntt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtwwcndhrp.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtzukcutmp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhixingplan.top/Article/details/gtpbcjlgxd.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gteuhcmbpb.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtmivebqnt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtnzulovhd.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtaaapbomq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtkpnmotlr.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtlooqlrkq.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtqsworphx.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtparjrezq.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtulcndzjt.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gtgozpwhkt.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtfilwkhqs.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gtsnpuflqd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtkmopmkrj.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtlhljdrtz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtnctzaoyp.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gtdrvdzubw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtvnlkrdmp.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtjwufwhav.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtoihfvgiv.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtqbswyyyh.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gtxtdtdejn.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtjaypaygh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gtzpvdakue.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtwblfvzux.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtjkbdwsnb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlpkouysc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtadohaylc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtptewrmfk.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtbilljpnn.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtpbdxddfj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gtopsvdddi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtxqzrisob.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gtkjaxoolr.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtrvxwdabc.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtwjdemafq.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gtfrliwsmo.html


<!-- 参考信息 -->