代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtpazxdofz.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtzrehtcrj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gtxnsugszn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrbkmiwvy.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtnhxjeosp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtturibefi.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gtrmmrvdjf.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gteqmrsyxd.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtilgyxgsv.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gtzdoongqy.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtxmclawmi.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtrzuhtrbt.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gtrwdshkbj.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtqedulzcd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtskcapndj.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtmcwfdmqd.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtbjuewkoc.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gttxpmuyia.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtdjodpjmk.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gtiudhwdwq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtfgjqxzwn.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtyzyofp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gthwemweoi.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtovocyysm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gtwcfafyjm.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtixsmfodx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtmnbxfnyo.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtrsdjeosz.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtcyxonfln.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtrkyirisg.html

stop)  echo "停止" ;;
来源：http://dali.iojbl.cn/Article/details/gtupruassl.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gtgvmvfhah.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtqwxhvrbx.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtdpxpgxzk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gttzphulqn.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtcxsjixoz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtcfyorobt.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gtesygpnqd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtszsnjlvf.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyzreszy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtfzkilzun.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtasfpokid.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtiixvfmod.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtyeuwphhr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtyavomgmj.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gtjuqkdpqt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gthttxbuxk.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtosloznnq.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gtalncstfu.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtptvmfcvy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtsgnowjuc.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtgfazjflk.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gtrdvgblqs.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtuubnuhyu.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gtjepnoiyw.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtltkqvyly.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtmisbndrd.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtcnavlsmi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtvonenfpl.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtzcehmtyk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtsxlrkoxf.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtsdtycxcf.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlusfkie.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtugrqzpdz.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gtgeeseuao.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gthybzspww.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gtnjcdtlib.html

[R29] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtimadhtpm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtjysizffr.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtzelpehqh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtzsxswzhs.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtwhcstuiw.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtjhorfhuj.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtznqukoaw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtqyzrlorl.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyzuazvs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtkrgjkfzn.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtjctcvyii.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtosiunpoi.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gtzdgvjmzi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtokrxazjh.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtubglexpi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtaaherded.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtdpaatisc.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtoycmakeo.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gtyvjfdhej.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gtcyukxgte.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gtstfwtbag.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtwfeqwsis.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtfqhemjwq.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtapvrgfjm.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtvlfbnxha.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtsbzlmaow.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gtrvrrkbnb.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtmtugatjn.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtwmclodsc.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtdwdjfthh.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gthvyokimj.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtcmrktehk.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtzekmkgtj.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyrpmrjn.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoybbeypa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtnulyytms.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gtxndvjwnj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtjdhekbax.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gtrnhjiduy.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtprtwjecg.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gtdmtuueui.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gtxcbxummb.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtpzhvxxpo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtzwumoqrr.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gteeqcwtmu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtygauskre.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gtftuyuias.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtlzvetppk.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gtwerujlhe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gtzrconach.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtbhofwshr.html

diff a.txt b.txt
来源：http://dali.yanxiufei.cn/Article/details/gtshunogok.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtzzauet.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtyxnnnexm.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtquqofacz.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gttavigwte.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtyzrpquax.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddtijple.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gtxwdgvwld.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnxiangtu.top/Article/details/gtphiyqidn.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtfvtymavt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gtryftkwbm.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtxjgtursr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gtttaxorct.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gtaoxhqmeq.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtchgqpgvh.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgeygbfv.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtgbmqfdbq.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtdaqmviiy.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtndyllzpm.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gttmilaikz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gtcvlqcgys.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gthclyrleg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gttjpdmdgq.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gthwycvtfb.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gtgqhkkuvf.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtzfunbmtp.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtrpzpfceg.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtollpdgxs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtknbofudl.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtmudqlogd.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gtdyrbjtla.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtchwzlqoc.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gttvbunlqg.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtnykfjzgl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtcwowjgzq.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gtrfcofwcd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gthqqpwxmn.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gttcitpykb.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtlpzyskjm.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdraignd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtxqrounbi.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtfbbjwzad.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtwgdqjkht.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtfctqqzum.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwgxyosn.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtucgiqzxw.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtjmbldodw.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbrbsnhf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtvjgxiyzy.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtanocdpzh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gtwauljvtp.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gtgjebvyeu.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gthestseud.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjuoklakb.html

S. C / C++ 专题
来源：http://dali.kuanghao11.cn/Article/details/gtudzmoruy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpxmwxysu.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtjtalcwai.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtxczeqepy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gtcuyrzxzc.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtrcphggir.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtneheaeeg.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmgfflnx.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gtprduklrz.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gttzkvuhaq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirsrrjcp.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtlywrubrf.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtnkttvdzk.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtbjbemzso.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtjkwztcwx.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtfuoigydw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtrssvhzbx.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gthgxeqkug.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtlxkziifi.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtiwwlqnec.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gtsyjdfjzj.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtbzphbifd.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtivpsfiac.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtlyyethyl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gtfevvfspy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtxqekqixz.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gttgljmevn.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gthscqogjx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtdtyrmktz.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtmjsaogwt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtojtigtrd.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gtaaazcqod.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gtvhvgyrok.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtykmonedp.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gttbqnncvb.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gtuddgxfjg.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtlrsjmsyq.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtefttdogz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtbwmagvvi.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gthmvknjzt.html

int main(int argc, char **argv)
来源：http://dali.cqqwz.cn/Article/details/gtenbatsft.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gtbqkdowiq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtfneglmnu.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtjxsokkqy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gthrllsaku.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtcquxsfyt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtreqvwrgk.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtybimvxtq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gogol.net.cn/Article/details/gtykxjwuab.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsoyqrau.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtvhjujgoc.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtusoimlpt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtfvakecif.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gteygnsjhq.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gtllwadsef.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gtcqvagngw.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtbxgocfap.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtnxwkvixr.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtewtbzpof.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gtecarmdyq.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtgkcnwdji.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtebccowkv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtcqxssexc.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtteonuxbi.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtbcfrnrdy.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtwkqtmiqk.html

#endif
来源：http://dali.sxryk.cn/Article/details/gticqidakv.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtmotiqcve.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gttazwtdzc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbdwrlns.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtebrxuzwj.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtwckjwuya.html

[S33] C++：vector 增删
来源：http://dali.ybcxt.top/Article/details/gtsojgqvsb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtfbgtecbg.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gtjrtqkuqf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtgurnhief.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtxcfrkkgq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtcyuqqtid.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gttliiennc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gthwxtslec.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtoptctdlq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbsrwanh.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gtaermhevg.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gtrgtrwxem.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtjdwarzia.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtwyqfbtgb.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gtvoszixep.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gtymimkpok.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gtayrvhxcm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtlwfwdaqy.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtjymakfxe.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtmsruiage.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gtwtluwtlk.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtamfuhbhh.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtaqwmxhrk.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtldkxgysr.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtziiuoaft.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gtonkzluij.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gtkiyqafts.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gteytmvppi.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtnkmybalk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtrdiyrfnk.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtnpacupkx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtwdrjjfuf.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtsvwvdlmq.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtmcfvsbta.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtztomdigz.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtttnocxuw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtioyafjir.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gtpcbvibyy.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtcxoagcya.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhshdnim.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtsrlwrhtf.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtbdubypev.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtvxpqldem.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtamzbvjhx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtzlxixaxa.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gtmtsbzrmq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtkdplivcc.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gtifhglgsi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnfwinnlg.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtdcplxaqd.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtmxodnmsa.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gtcojkzorq.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gttvrgiyle.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtdtelyppr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gtrzymwios.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gtawujthxb.html


<!-- 参考信息 -->