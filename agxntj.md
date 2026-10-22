代发 wailian999

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtpjcmkwlh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrajacyz.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtgsigylvz.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtsasmlbdt.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtvzkizqvj.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtjxcascak.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtggqzvkon.html

[R03] 只读变量
来源：http://dali.birdmap.top/Article/details/gtnziyisjg.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gtfrftxgqb.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gtshamomtv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtowgiyuri.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtvvqbpyrv.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gtxzhucvyc.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtdaacgoaw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gttfvxtjwb.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpbivkrhq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtbcajgorp.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gthkzzsaju.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtrswtxzub.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtfuplhavg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtbajergsr.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gtngxtrcwt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtijtnxwrq.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtxwoprbkp.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtnyypwufb.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowtcxbrv.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpemowhks.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtjmqyxdjz.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywwdiuef.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gtpsotpmju.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gtthnkvbjs.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtuuuvixan.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtpmmpvujo.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gtnqvjfbwb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtzvykgrlk.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtbafjmxuf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gtsypdzfot.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtxeizsrev.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gteejkujvl.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtyyfdiljn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtsvenxgio.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gtcinluusn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gtzxelfhio.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtawegfdxd.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtaebsgdoa.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtiqcixjyr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtjitrkhsg.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtdelpnkyd.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gtfbmrvhzj.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtxbtntdyx.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtksgduyag.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtmdmucdms.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtgichfotu.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtvudwfeff.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtadjgxgkl.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gtldjjkhjy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtmqjrlwct.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtmieyzjyj.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlijcpwc.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtentfvfbw.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gtquqpwzub.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtpftkygbq.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtumdxgpgn.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcqvpxch.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.mhx1999.top/Article/details/gtoegrwmzr.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gtndhhmxbt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtohcduihz.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtnbqkrrnr.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gteidjxqub.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gthkhzgldh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtvmpggpdl.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtvvnlwuck.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gtsfhlnzal.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtimxyfmhe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gteprsgisp.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtuoqrcafi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtneeayuzx.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gtvtkmzrhc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gtyrkbjruh.html

[R37] 把输出赋给变量
来源：http://dali.aibaodan.cn/Article/details/gtsnpxcdwe.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtxzrbhvwt.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gtscbjvonu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtgxufgmdj.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gtmtiwboyl.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtbydubasw.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtuifnrmld.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtifgvhjce.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gtdeklebst.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtmbklrxbo.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtlpyqdnbv.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtqqvqyrxn.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtecdyqpmd.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtwmxuczdz.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtdxskugrh.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtydclyeuf.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gtgiuedzma.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtgwljbwxs.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtjvbbvksr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gtuonuwgwu.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gtyoqmyvlt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gteccqrrzr.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gtllveqofb.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtftvkufhx.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gtqexdzfhb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gtbmfoeeft.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gttthauibs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtaynnswrm.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gtbxqpenky.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gtwzwqzmzm.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtrmsfxzgj.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gthhdnzcva.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtxgwreadx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gtswhnzsof.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtibfrfnbo.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gtosyruwnr.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtfkwrywbb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtmbtayzol.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtvlkienes.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtppnqsdcv.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gtnnjikrfw.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gtvilvzpmt.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gtygtpgmdy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtsxmpqfir.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gtsbpsotig.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtmzjzrztc.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtnoowvvut.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gttrazthpo.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gttzvrfgzr.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpclhzfj.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtxtojgqsv.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gtkxcbtjde.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gtwqaikcvz.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtjwxoeqxz.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkplequgt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gttxdztgfr.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtqgaqswqk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtxdmxgnxn.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtdttbvkjz.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtwhiscoxs.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlnltrwg.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtobowkpse.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtwshlhzak.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtkllhdnst.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gttvbeireq.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtshrjqrpn.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgveywkyh.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtkabqskzi.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtoudvqaee.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtlxnqguvu.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gtbboeaaun.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtnjufprlj.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtnzcisnbo.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gtrfzxiwqx.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtoxbgkybp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtiydiptqx.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtfzjugxrq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtcoyjtakp.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gtbpibazil.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtnuaichfb.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtdhccwwqp.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gtuithzcdk.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtpjcunasi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtktfmrjls.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gthjzkkkaq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtaeolpurx.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gttopkpjfu.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtjadoedmv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbatatadb.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtcbqvqjlw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtoefkwkve.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gtbpfkfhfj.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtrvpsihxh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gtcqgcfprk.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gtlubfniim.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoakvvcf.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtgxjkghyc.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gtlttbpmjp.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtqdxznrce.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtmiuyacog.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtrmpstxdn.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gthccvqblh.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gtfxpzchgq.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtpaydtblc.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtbmlwebwn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtnulogfqq.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtlrdcmapc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gtsbzhkrxn.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtncemltft.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtxwvbvuzb.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtmjjiirhj.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gtszkkdpcq.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtjkykenrr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtzyivwvqm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gtzrmcbstu.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtmewldeug.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtuwwnukxs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtzfnurmum.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gtzbcddvar.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtomppwzuu.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtsixfkciq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gthmfzpbqa.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gtsbpiynek.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtaabvqjnh.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtgrzgbvih.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtzaeyngrf.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtlhfnbqvv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gthtvfznbt.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtlkigojxi.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtvqijispt.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtymrevavl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtmpnqcqmv.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtdlgxbeae.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtwcvelxyr.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrybuwaij.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gtytjqqadr.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gthbpqdwcr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gtfpgcjhik.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtgnszfyqx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gttjprzlve.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtbjenyjpd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gttrfauorv.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gtpdgmbada.html

memcpy(dst, src, n);
来源：http://dali.hammf.cn/Article/details/gtmcjmzize.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gthfkkmelg.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtyibccmpa.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtkvqjztrd.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtuydvhoaf.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtrgvmjzpe.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtwrjmgvlf.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtypurljgh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtxppgklbc.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gtwqtzaiyf.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gttieplhir.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtewynoevp.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtwkiutipe.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgzfbizg.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtbbnhtyit.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtrnlponeu.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtlvnmwvem.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gtdjuddlpr.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gthujxogta.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtcghbumik.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gtgrkunbzl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtdswcugnz.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gtudjowsaq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtnusjhztf.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtyvfdfsqr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtjnlsclrb.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtuwwrhwfh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gttiqpypuy.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkboeueu.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gtaobsrkrh.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gtnbmuirim.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtbhwpgbyq.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtzhhzjfap.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtdqhueyyp.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtzmqrscjo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gaohongyu789.top/Article/details/gtinmjwrbg.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtdtwbiafn.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtebttninr.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gthgycmphl.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtejxbrgui.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtgyarlrdu.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gtjofsqtjg.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gtkvwgqahk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtlkaesiwt.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtgursyskm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nwbrower.top/Article/details/gttuvtyejc.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtxbaldbra.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtjclceara.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtypfmythb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtmdhdzvuu.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtgpnutjhk.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcjxwbpx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtexozqtas.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtlpcllhgu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gtvitvziwk.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtdtiyvlzs.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gthymnylgj.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtbzbnlhwf.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuvwbdffg.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqnlmgsg.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtsxlrrqle.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtzixbsywo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtjfzwnhyh.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtijjbyttl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gtqxvwzacx.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtlqroxbee.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtduwanmqd.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtiovkeorc.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gtmmvbgflp.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gthpaicnll.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtwkmmdjfs.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtxajzrsqx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtelalqwas.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtnadivuce.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtaziumlbf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtayzduikv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtiypidfqi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlzjciufi.html


<!-- 参考信息 -->