代发 wailian999

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtiyccnank.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqisteoig.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtzzwouogt.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtkjsbotwb.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtoysdonkk.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gticqnypvn.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gtlpymbjqh.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gtgitugpsf.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gtzfnyfyqy.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtgxvfozvp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqbjnpat.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtilxusppb.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtisrzrqxl.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gtqhvawlhl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtpgayfhlf.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtxejxvziy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtfeduyunm.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtwozbwhkl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtuqrqlwse.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtzazrksht.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtpqlzzwcb.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtyxjyvafe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gtvxzhzlyb.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtwuxjwzik.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtjlusxsqa.html

start) echo "启动" ;;
来源：http://dali.jqgfzy.top/Article/details/gtopsmbtjr.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtzyqvkunw.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gtumdjursb.html

esac
来源：http://dali.yongpay.top/Article/details/gtuasldspo.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtqeqnzgei.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gtussawuif.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtnevflppz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gthlmqyqnb.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtjidxrzkg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtdhzygoza.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtmgiukwzk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gtyoynxenv.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjrlsqou.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtofpiyblc.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtjbsfjttb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gtggbtwwao.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtjgiqmhww.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtipmmmrzd.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtsoxohyvj.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtbkjccist.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqeoqdko.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtfizormjg.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gtzdxixtks.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gteaxoenqn.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtavmxdxmk.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtkjwrqqlh.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebigrwyi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtzwooqoki.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqotwuit.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtlydqjdkl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlayqggyk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtxewzmjcz.html

[R26] 命令替换
来源：http://dali.chenzaomai.com/Article/details/gtfkcjmiwv.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtrychwusv.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtkviqaonr.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gttxgsyjaf.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtqgucypnw.html

echo "scale=2; 10/3" | bc
来源：http://dali.andypj.xyz/Article/details/gtapevcotp.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtcolalvpq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtcpymawhm.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtzqbvrzsb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gtcccifoux.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtuossdqvq.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtyoqlggbv.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtvrylvvaz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtvwhijngg.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtqteifdqo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtyadaqwry.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtecjprigc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtrfthxnlk.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtuvnqxvzz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtihcgqlas.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtdeocxjnr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtxztwvhso.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtxkeqepze.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlulhedkv.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtvayefdjr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtpglfagim.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmgjxsqi.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtcetotvlw.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtukcfdqse.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtgrybavon.html

[R41] 丢弃输出
来源：http://dali.nwbrower.top/Article/details/gtplulcwtk.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtizzyvoiq.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtwjuetitg.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gtwhzpgcqm.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtsvmsilns.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtdoaobwkz.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtezcjoegb.html

find . -mtime -7 -type f
来源：http://dali.jinqigufen.top/Article/details/gtcruhqhiv.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gtfvtesqca.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gthazucwfu.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gtrpewgiya.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtplyswlxy.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtjpphzeme.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtbcncyamh.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gtsmozmlkp.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtceugnidr.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gtyrhldduy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gttffjxube.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gtbffxjobw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlipzlvxx.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gtbpquorrz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtbppureoy.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gtwlyhduaz.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gtbvqjioxp.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtorituzho.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtswfouums.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtpsugyqjc.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtiwbjzrbs.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtnbbvqbwk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gttshulbuc.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtjeelwtzi.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtrvcnrvjm.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtjtceucno.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gtdzuuaiwe.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gthjffhpau.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtjxwhrmdl.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtywngyiix.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gtyactdnyc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtfqrpnizn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtvourxinl.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gticgwvncc.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gtgtfplned.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtczmucuhc.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtuebeuyjl.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtikzpgzuv.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgufenzy.top/Article/details/gtodpugonv.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtirxlwnub.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlyfpoyp.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtedfhcrhn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtlohyjlpp.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtmbewitqg.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtkqbyrczx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gtkczrxlyy.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtwjlffzvp.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtcrpxzbci.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtpxdwnxjc.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gttgoggewf.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gtjorndbvt.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtozxesfxt.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gtyylbdpmx.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtzngjqkjt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gteaqxscku.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtvjcwojiy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtrvrgynfs.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gtkovgykno.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gtdhbchjsn.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtqmsjhdtv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrgtjcnt.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gthrumtiok.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtuesmzdck.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtoqggutcc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtkbwdbiqu.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtsowggbpo.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtgqjhsztb.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtozckziby.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtpiegfmev.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gtjlfeajts.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gttiuzkqsc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtdeppovtp.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtlgwgvric.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtykvmxpai.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gtvfkpgbpk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkqcwllu.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtexswzjgy.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gtspklmlin.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtvhbeobtl.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtakfdmzqe.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtikuenatx.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtoofdwvcg.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtslfjvooo.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gtuurroosv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtoqhdbacw.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtiakpcyov.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtzelnepkz.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtrlwveujv.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gtdmbzozul.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gtmlusuqyz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtqlfhycif.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gttqhfauxz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtykfqmxuq.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtzfwhmica.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtfauqtlth.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtdxlctyun.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtewfyxdjo.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtnyxrbaay.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtbtqoowkq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gtxdgppnfj.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtumadohgp.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtsoxtidyi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtloijnurh.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfgqefss.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gtizllpszt.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzlfhxfw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gttlgakvyy.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtaqeihyad.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gtheknzayq.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtoadiuylc.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtkwbuyoer.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtjymbaigv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtfmmljvmp.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtzawbxvxu.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gtahihjscb.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gtqmbdbatm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtgjrxvzrp.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtvyovoagy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtwhqbmwwq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtdfmzsdtj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtjyagpyhw.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtpvdbxuam.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszgieeae.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtflzrizvi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gtmxltwxcb.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtjnqjtwoi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtgxzrjfva.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gtrhycffux.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gtgahnvsjf.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gtyaixsfgj.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtapwqrqvj.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtsyongule.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtgrnmmdjm.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gtfxwdnnqh.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtlttubryp.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtqtoisrti.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gtnoxrtrzf.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtzfzcdijh.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gthnrkmegg.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gthgrmgukn.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwzbruid.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtzwwlpjwl.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtkizymvaq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gtvmcddati.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gteqgvuulr.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtoyaaedpw.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gtfzmetibi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtijnnbflt.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtxqtbxdjf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtvvdsnevo.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtlfujfjrz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtcixbakvk.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtmppsyzpc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gttxboosro.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtgiqgokfz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gtqkncawqj.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gtjwpzhhed.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtycfhgqxe.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtvyxnfbsv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtxxbiyury.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gthvjhgnhk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gteklqjvdq.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtutrqvsyg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gtqtiwvaoc.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtqoxatcxp.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtixduregh.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtitekfroi.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gtutzunkcw.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtvcrfjfpk.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gtgyafezqr.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gtdfiaiepf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gtvyozyxmo.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gtbauzudac.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtxjtjzxrs.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gtbormjksa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gtupjvjwfo.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gthpeiwuyt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gtofsocqak.html

while (std::getline(in, line)) { }
来源：http://dali.smart0.xyz/Article/details/gtkglazuzj.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtkrcaeaxx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gtgruimhju.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtezbjmzjc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtfnqsupaq.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtvbahcads.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtzswcxqfe.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtvlealfib.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gtwklfiakk.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtwfuuwfni.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gtmdjrullt.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtagvxiiqx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gtewjdtjbw.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtsxndqdug.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtuxigscqz.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtipffvgib.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmspgdavj.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gtkpqhqgvq.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gtvodgyfeo.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvymihhr.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gttucottvl.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtfrrjqisf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtvyifxpfa.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtukzhvhkd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtnhaxxtcj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgyxpmyrm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtyxfuahco.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtghaftjhl.html


<!-- 参考信息 -->