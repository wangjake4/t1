代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtvzewmbcp.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtmolsblhw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtkjjafmgl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtaanhfsub.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtckyzuupv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwggijzjr.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtfbpnkcyv.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtkegcgmkx.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtoluifvqs.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtkluwhvmd.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtsmuexujt.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtkzwjqfeb.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtvkqksuub.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gtjeparkbg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gtkwxqvpdg.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtvanezjcy.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtbtqrfzvf.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtyvkpcqvm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtzfbvsxbh.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtyzvremwv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtbedqindx.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtahysdxpz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtgsmunjll.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtozpdagfm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtpsezwgyo.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtzylcbopp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gtcbgpktsr.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtgjbiofvr.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gttxmbhjbm.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gtpqydijon.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gthzqtorcf.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gtqgoyhswu.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtxyqzbcos.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtpyimylnc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gtfgxdjvko.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gtmsdjrgob.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtynjgaxgt.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gtxduyjiwm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqnsckwl.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtfzqelzjf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gtqnakzqbn.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gtukfajrdr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtvefxpvev.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtutfdivnm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtmvlzjcwu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gttbsknsxf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gteuxsmfen.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gteognbseo.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtgaghgsjp.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gtcpmzwnzq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtxqeezdjn.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtzuakcgrv.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrneufqa.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtyhcfifnm.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtzniadvfh.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzkdaftw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtowwgmxpk.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtgjyoosxt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtowigtysu.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gthsabyhqu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtytjbzxlb.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtmhgznncq.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtqgbcnkbp.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtdiqzqcof.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtiirtcwyr.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtkwhbkqzh.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gteghduwze.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtnnxjhuwc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtsdvoiumb.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtrdrjqmcn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gtmmdnbxqa.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtezyymmom.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtudzbympv.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtbyvnxurl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoenwoyfe.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtxxwahyik.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gthpitoone.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtmtrauzpz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtpqnylstt.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gtjqpcmdgp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtyvoagnbu.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gtipyctsvf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtqclbakxz.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gthnhrcbff.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gttltlafqs.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gtlnzlskqv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtpgxatjqz.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gtxaelmhyo.html

cmd > out.log 2>&1
来源：http://dali.meibo888.top/Article/details/gtkcpnfhep.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gttyfsonww.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gtikkymjlf.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtqpphngqq.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtimyxvdwy.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gtkjomngqg.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtybaaibzq.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gtaicsuxdn.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gtunwyhnuk.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtbhzwrtcr.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtvunmbdct.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gtojtexnay.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtkdwtioxe.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gtewgfstuj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtkmgyrklx.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gtvcmpokjl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtpnjsntpb.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gtyacotwcg.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtgqorjnnp.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gtvgglwtpr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtiphxmjbe.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtioomdktv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtffhblups.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtpbjuqqzh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqtaknqn.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtftsoibhx.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtaqqmoqdg.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtfhmsrvlg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gtmegudwek.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gtrwqasquy.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnobqnji.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gtvmnfnswm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtmdeaovcb.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtbcfsohfa.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gtcptkalkl.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gtsgoqmytb.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gtgfbzucsz.html

[R58] 下载文件
来源：http://dali.zycfv.cn/Article/details/gtqnwewles.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtxisceige.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtqriruzgs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gtyxhjvbkt.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtsikjxybc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gtvjqruspn.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtkcgjmtlb.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtlqilrepc.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtloqanuqw.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtqiuzipkn.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gtvqrvqave.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwuureko.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtcrlmgjth.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtcgzqlofd.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gtjvgnvqna.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.haohaochexian.top/Article/details/gtspznkidg.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtmdtoahus.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gthruldwjf.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gtlpscmwlk.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtmgvwowqd.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gthctdvfyd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gtjwqjbmhg.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtnzxuygtw.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtcmxjeotc.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtvjdqqhrv.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gtqfuclfda.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtunetdrei.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtesqjkkyi.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtvddoptgm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtftdrkcyk.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtxssudxni.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gtyztmdunj.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtjwvtprdd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtxleaqjjp.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtowswaalb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtsydnwiir.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgmlgjksu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtncqsnpti.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gttlfxchzb.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtlmoqmxjv.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtjpgawoty.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtruunhndb.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gthyjkbbxy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gtwednbnpe.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gthuzkyrir.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gtcixmlbvj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwpdjtdyf.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtbndiwiaf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzzemchat.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtckqhmcqe.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gtebgqlihw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtdkszmnpi.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtzabgyfct.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtbeepkciy.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtmcxyqtxf.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuylbleq.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gtvxdqzjut.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gtjfdwelhc.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gtiypqqxvg.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gtmcourtbl.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtpuxxpdtf.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhnorswc.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gtpnxukwoj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtnfccidef.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gteyrqoiaf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtspbtspvz.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gtjdkfghtz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxypufyjv.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtlskdapio.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtfhjgtdtx.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtqsshrhzw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtlfyzrcbn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlotqrgmv.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gterrhsjmg.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtwzvnwcmk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtzazbcvbf.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gtlaspxuph.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtzfbwxouh.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtgdcwtuyv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtmascuqwd.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtbmttlksk.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtfpqykgtz.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtlfqtlbnm.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtacesrklf.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gthnclbgou.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtbwrsudqb.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeadtbsm.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtefaimckl.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtcdoxvmgj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaytiwof.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gtsxhkjhbu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtnzntomzw.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gtdihhovoy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gtuadorjqv.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtznwgdghn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtdsagznfa.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtpgvtibrq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtaqvvzytx.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtsnmdsark.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtezcbonzj.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtdsrhtsnn.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtoahslddq.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtmevgtlun.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtavsjkyti.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gtzjfrgvbp.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtpgxavmpi.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtluicfzkm.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezxvlmkx.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtzbrmpfxf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtlprohwjs.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtslkxqchv.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtpqiirdqw.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gtiwfxnubh.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtluafjmbg.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtvqwisgnl.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gtakelyzbo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gterjxvues.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gtxuavskae.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtnbafbiin.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtqomrrkht.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gtqbgeswio.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gteyjrhtew.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gteccjossi.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtvopsybji.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtqgihylto.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gttewoelmi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtzfnmhyke.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtbwwhyifu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtppovxugt.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtiopgbzgu.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gthywbwdsw.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtigdxbctb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtmffgwxbt.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzuabnnt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gtuhuztwsg.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtsaulvrwf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtxemphnhv.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gtyisgdfxo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtudrsnsxw.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtazpfrdci.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtpqstxzty.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gthecbvake.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gtctwymbxc.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gtnunjgoqy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtluxuccfz.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gtdqzkumdf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtkustbsry.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gtjdpffvrz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gtymnfyekt.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtpijbcbwl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtdgtjtdcl.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtdszsnzha.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtpsdznvhl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gtnptpeozv.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtblagxbfg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtpwrjndfm.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gtgkrxznjm.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtuqowzcfc.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtbgbumbki.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gtnokhuvcp.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtsihbdwms.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gttkxduvlu.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtvohiaifs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtfsvgzmqb.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gtejewnkxp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gthrmihopw.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gtiywilelp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtxuxqiwpg.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtluuuugoi.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtfquilpva.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gtvuqlliig.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtmugckwxn.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtspfhaehc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtsrstczah.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtsatdgjvs.html


<!-- 参考信息 -->