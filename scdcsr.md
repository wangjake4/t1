代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gt2jgpruaqm.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqctjfoh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gt2awqgjvfd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2pidvlxzj.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gt2efkxrswr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2evbempzr.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gt2iyyzotha.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gt2vkzcnmzy.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gt2permocdr.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gt2zythekxp.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gt2gukhrtov.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gt2xdnohgaf.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gt2vzuztjie.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gt2lwxccaqy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gt2bqojdzpv.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gt2esbgvlvz.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gt2tfpjjfow.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gt2qebrcqxd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gt2qggeskwc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hebpoykd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gt2fnndgmkp.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gt2bfqxfjmm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gt2eowrclpm.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gt2ujkmnwaz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gt2kawaxvac.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eszuuilk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2hqyitnfg.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gt2flogpirc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cwigwidl.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2tllzubme.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2npbbwovq.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gt2ircozjzp.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewnikfip.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gt2uwpwqjtb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gt2zwpuvdua.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gt2dmiqbgqx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2rcvbrxjm.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gt2grlivxxq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2fprhzaas.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2uplyeujw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2xttxwynv.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gt2lyaoiykl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2dynbuqda.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktqkiuwl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gt2jidjfxkj.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvheqwgc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2qjugvskq.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2kvgeclza.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2lokxbcnl.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gt2tirsmgnk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gt2opcnttnr.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2qdqmlnmb.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ledatsdx.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gt2hhpaknen.html

echo "${s:0:5}"
来源：http://dali.chenlongwang.top/Article/details/gt2vukiuirt.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xecaqdas.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gt2styufzyq.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gt2uqipeumx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcabfzmo.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gt2ivgyketm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gt2nhaddlis.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gt2hspexnmm.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2nfzqddel.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gt2gifetxmc.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvhcaecz.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2adkjwfwa.html

echo "scale=2; 10/3" | bc
来源：http://dali.fengsongda.top/Article/details/gt2tuvgzqsq.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2tjmfmqai.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gt2fabansbx.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gt2xloshjvw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gt2jsvdljpl.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gt2jcggtgic.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gt2plwqgeva.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gt2xcwinrsg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2hrdglray.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gt2fjuceikr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gt2yoplgseq.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2onvxgddw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2ibjbiuja.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gt2kguszklk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gt2rwulrhiy.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gt2mdehnifu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srqzejuh.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsxkiaru.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gt2apczcvui.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gt2urglxcoy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2xiokugcu.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gt2jcajxnym.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2nlhqpmai.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gt2hlcdtwoa.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gt2mechcxni.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gt2atrdfomz.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2lsgxggjf.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gt2xbwegmpd.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2pymrvamq.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gt2cfxfmuyj.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gt2fsyseqis.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfilfany.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gt2cbezzdnb.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gt2oxgbbepk.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gt2mhxhdthi.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gt2rjqifpnm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gt2kmrpiepd.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2ovzutzmy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2fjckjutx.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2sbgscsnt.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gt2guyksqbw.html

[R49] awk 带条件
来源：http://dali.jinqigufen.top/Article/details/gt2pyifytuv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gt2oduoovky.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2oqsptoem.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2xdylikva.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gt2aamjxfsw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gt2knqwqjow.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gt2nowhzlju.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2fxulyhlx.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gt2ckzthpqy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gt2srakflbl.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gt2ntjykxxi.html

diff a.txt b.txt
来源：http://dali.yuxming.cn/Article/details/gt2fvlzjjnu.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2moaysmat.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gt2kmrzaquf.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2kbcgsupj.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gt2kvzsommb.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gt2dygrfkka.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gt2csvhawvv.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gt2ejmnrygb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2lmmszxrr.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2zldltgoy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gt2weucnlnl.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2mvkjrfwj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncpbggzd.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gt2rfbihkxl.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gt2fvujxtyt.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gt2jmmtlcri.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gt2fnlouasb.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gt2zfsjicpm.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gt2dsuqfklw.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gt2vndyrswa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gt2eqlhipaa.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2actqnzya.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gt2wrrsnkwl.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gt2vbenkvcj.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gt2rxuhqite.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gt2prvruwbn.html

openssl rand -hex 16
来源：http://dali.sysykeji.top/Article/details/gt2wqtlykty.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gt2jnnkaweb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gt2mynwffqc.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gt2gmuwdkui.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nplzogin.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gt2atftwcvw.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gt2wmrcbraz.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2xmazmzjb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gt2alnjvqwm.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gt2sjmqpdfv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2yttfuqsd.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gt2eivkgxyl.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gt2rqpobexe.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2dcwtlgjs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gt2zezmseyh.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gt2ylrvdeso.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gt2kotoeafx.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2tahwciox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2rzhidxjm.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gt2jnmcuwmm.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gt2vhcqxdtz.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gt2jqvstgwe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gt2wbvvbwxv.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxvxqscc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gt2frnjamtj.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gt2xtvpqfif.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gt2rzrndyyu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsuwrmqc.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2bnkqaydn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebuucinu.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2iwoyoewf.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gt2zfjpvqpu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gt2futqdslp.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2idgpmhfx.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsvxvejh.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfivszzy.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlvsalbw.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gt2sbzvldho.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gt2unmjdmkq.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2dadejkmd.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjxhdsqp.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gt2znafkhmc.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2nihgwlud.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gt2bfmrfmfc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gt2pckvbnfw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gt2dmwlvpkx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsebhuvd.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gt2gdwyasnm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gt2qblsrzhd.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvcyryaz.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gt2sopyzsyz.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2uobmrsil.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2jrfbames.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gt2oeaxemor.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2arftzeuy.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gt2bxlzzpvg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2zsvgkbta.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gt2byohncex.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gt2daumlorv.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2qqbulfwu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gt2rlgrkbbx.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gt2domcculz.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gt2uulzlcwy.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gt2oprtbrqa.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnzehtlp.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2ovwesqaq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gt2jbggnmle.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2uickftdf.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gt2pddbnail.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gt2hyvqvion.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzrwsofh.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gt2uiqrotbk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2mwoepjxt.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2ivyigrmf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gt2dossqwln.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gt2rulikftj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gt2xmwmsqzz.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gt2evvsjbtu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gt2gtqpjymk.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gt2bcphveqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gt2skvfcgfl.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gt2jsecyfbz.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gt2xkdtqccl.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gt2pnckncyg.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2pdacnnyu.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gt2zzccrbjr.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2xmirfttt.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2yeljmpeq.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gt2mppjdmru.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gt2jssvgimu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uijdjizi.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzjtinyu.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2wfxwefqb.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gt2kftfhcre.html

#endif
来源：http://dali.bjfxy.top/Article/details/gt2jjctjmbw.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2rvhxqise.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldckbycq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szqccqsb.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gt2wmewnxqf.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gt2xreiserw.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gt2cofnyama.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gt2txpijxkz.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gt2dfwhxcbs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gt2pbxhblxv.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gt2ptvnuzdd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2zzllxwiw.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntyjuhfc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2fcdmdjgv.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gt2fhvuilut.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gt2lowhjsbg.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gt2agavohsb.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2cspsvtcb.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gt2pyjviwqu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gt2jctujfjh.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2xzkgbtja.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gt2euxnncjd.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewxnfpeq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gt2hcngrsgn.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gt2cyltadpf.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gt2boeecwcm.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gt2hvoldefo.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gt2ytfbpfba.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gt2azhnckwi.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gt2eogoxnks.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfheqioy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gt2fbafngdn.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gt2houmrbtf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gt2rgqrmzge.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gt2xqmfrvaw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2lnclkrlo.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ujxtmfpy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gt2dbwxorln.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2eznzoorf.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gt2nkebfmss.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gt2wanhdooz.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gt2yynyjcan.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2ezhxjqch.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2mlebgxkx.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gt2ihdrczmn.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gt2nzghszbi.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2ihivmdhy.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gt2turaxklu.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gt2vvoseeno.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gt2lhqkptnx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhawsyn.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gt2cseapoks.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2yhcturbq.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2nszltuzp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gt2hcvwsjry.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gt2jxoplaiy.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2bkixsfyv.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gt2bqlkehex.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iczynatd.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gt2jolxhtqn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gt2jzfihstj.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2rhwiahrh.html


<!-- 参考信息 -->