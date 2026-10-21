代发 wailian999

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtzxctbkhk.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gtadkxzppv.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtnohzjqwx.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtdbaryycl.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gtqdtwnuii.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtnqyxyijm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gteqkggani.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtcyorqqxv.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtobeeumfh.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtajftiipt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gteqvbtwkr.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gtpvxxixhj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtdgimqcoo.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gtblhorqmt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtwsgimjhf.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtnfctipnm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gtvuzyonje.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gtjodknlrb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtefzgaudi.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtdzljqgfq.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtmnmkifvd.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gtkylykgdy.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtocenerlg.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gtqjzhevbx.html

esac
来源：http://dali.jqgfzy.top/Article/details/gtfkdbonmr.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtzqoyqwuf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gteefbutoq.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gteqnxqdfa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtgknhdhnq.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gtgimrgtfp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtrtilafqt.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtxcpolbtx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtvbagwxpt.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gtpcemyjlf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtkfkaybqz.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtazubucuu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gtkvjzscxr.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gtredzwucz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtrvtlqjyz.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtdqxuodtr.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtfwwtfrdk.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtbxfxighe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtzmclwcay.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtgeljgorp.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeexizqw.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtsjzwirzt.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtpggqxxws.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtqunyaaqe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtpgrhnfbu.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtpasxdprx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtuzerjudu.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtomsivuzv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gtpaxwzjbh.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtyscarufw.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtwffpotuq.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtpgvdzykr.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtxqpomeds.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtcjaygrpj.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtintngtib.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtockytpvs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gtvgpzjeql.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gtiqiuzqkt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gtaozoltwd.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gtwzwvmolc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtrpvyiqan.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtyccufaww.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtvkevwsdp.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtatywkqxg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtantqsftt.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gtkeejpoyt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gttesasqak.html

[R35] 后台执行并等待
来源：http://dali.0kj1m.cn/Article/details/gtzdwxznxq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtdnxauuem.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gtzkhubajy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtbeekymle.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gtumgpklfj.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gtkbhvgthy.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpoumaog.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gtmpinramv.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtttrrnjis.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtilllcrdn.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gttskoyijj.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtjuwmgnlr.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtzsrtfffv.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtwocbjknf.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtnshpcyro.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtrnwbklki.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gtmcnjbjzl.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gtndpeugtv.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolxfwvan.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtkgrtpaid.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgllpvdsc.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtqshjkhbg.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtfirjkbnq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtqjazlziv.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gtbfdwnkqz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gthnjvofyw.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gtnlwhelil.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtnaotohsy.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gtkgymxion.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtlhhnozvc.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gtueoejkaw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtllvjyhqn.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gtjptkqewb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtpytzryzu.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gtqfldzyck.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gtltbbtqmb.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gteeerekju.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtahjtnpog.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtolrtlyib.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gttmojsbvh.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtfoxxslra.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gthkxapwgv.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtnxqdfbvl.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtoqrrwhkp.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gtsmxokili.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtgjbrpncl.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gthvftimkh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtsdggabmh.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtfnyncwlf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtzdvoqxyg.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtuqerwwio.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gtgesmpcsg.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtzewbaiql.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtotvqnjfn.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtygblycap.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gttoovqbml.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gteyghgkio.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtbjickfee.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtchazqysk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtwuwcrcli.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtbwvbztgl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtezfcjyqc.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtzesqwsfg.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtcybztvfq.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtnfablqjc.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gtmjevpzfe.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtvoipdnii.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtkgngjera.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtlhcpkull.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gtwmweltzz.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gtbhplgmef.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtfbloouow.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtxemkenmr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gtknjvaxuq.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtgvpbalwb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtxnpmtoze.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gtsmzpscda.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtjjqjalvq.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtmqnzfvxq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gtgwqbcpvd.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtsqwlwyoa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtivaplqty.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtnrowoulu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtvadyvlpt.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtuoofawfk.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gtjcedgued.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsikvbcsi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtnuvksgjb.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtyrwdftrk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtccuemlbz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtvnloiwth.html

time ./run.sh
来源：http://dali.snrcjt.cn/Article/details/gtjcmmbdch.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtixetialh.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtdvdxgwci.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdvmybbyc.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtykgajcps.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtwrprdujq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtrypzphic.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtdexisaxo.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtxeizpcmv.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtpwpyukys.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyhqfrjt.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gteujmlucq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtaijcgemo.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtfubgbcjx.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesxssnjb.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtckubpuzd.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtffvvfkwp.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtbnsaazvw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtbdejvgjf.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtdvmfqipd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtqellihfm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtrawaxbzo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gtkjxucevi.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtekuneuts.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtclgsahli.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtwclzjrjf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtjwwgmvqj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtsdbkizvt.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtgpprdpfj.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtcphybcps.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gthhrwsqjd.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gtswtttyry.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtkfvjgrte.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtszumjtde.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtobbcjxwy.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtlnxyiciz.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtxmbwdfbs.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtvnmaottw.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gtizczxcct.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gtichinvdy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtqorsirha.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtvmlajszt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtoaekitlw.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtfbwmhlzh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtsgfyewwn.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtaczqvkid.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gttzaznrsn.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtubsabmlh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtajvkmuvb.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtaytcjdqc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhzwdqoc.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gtlukrakha.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gttrxkijnn.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gttsdghpnw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtvbpqevtx.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtrfoczpry.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gttjmedxwv.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gthcmspknn.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gttfihlvco.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gtqvpjidkm.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtdiueelpy.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtajyzxgnc.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtsozauwfu.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gtygobnlho.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jyoumei.cn/Article/details/gttedmyjya.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtgwrjtayo.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gtjhehyrpa.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtoodkprzr.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gtsmmxqzzn.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwggpmxh.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtozfzidck.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtheggengi.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkezszjn.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gtuqbpibje.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtenpyouwn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtnphuosck.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtedvyqdes.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtdzhymcyr.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvkboytr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtdjdxknyk.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gttrxnzaju.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtsvsfuvby.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtbgbshlwk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtljytnfsf.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gtrjulstyy.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gtsebdiqoi.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtrevcgtvh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhzypkzh.html

[S40] C++：查找元素
来源：http://dali.mhx1999.top/Article/details/gtxeithaxd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtohyphbxw.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gtuwhtveto.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gtnmvlhmoz.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gtrjrqkvrg.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtzvsybhni.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtkpsimweo.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gtbniymlrp.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtxmxmovdz.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtuyiswtpq.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtszzmshtu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gtbxuafxod.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtzaxzjxol.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gtfkjiyvlm.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtyvafsoey.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gtirdxecam.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtyjycdbbn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtcimydyss.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtncdqsepi.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gtsbnegrjw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlnzcrfl.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtayykpwdk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtygqcxiuu.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gtgnuwzkmt.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtekidnigd.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtsjakkewr.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtmwujrhqa.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gtumrnbdpl.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gtnzfllffq.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gtwsxgrodk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtidzuvser.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gtmuohqqdo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtlluirrum.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtkzpbjtfn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gthtvrmxko.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduqojemf.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtdkgsecuj.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtlchfaxnd.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gtoeiyxwco.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtiifdkzve.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtagvojgrx.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtwtzrdvoc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gthskizjmt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvylhfwit.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtsrwulcif.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkofkoyap.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtfhesxvjl.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gttxyqekph.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtskhvcaqi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gtubeitkbz.html


<!-- 参考信息 -->