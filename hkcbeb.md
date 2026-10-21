代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtvqrpkfwy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrbtjpjx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gtkxvraqri.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtbdkbhhdt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtkrwrivtm.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtganjcrya.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtbqabazyk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkbehqdlh.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtqndvyigw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjfebsckx.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqlvgfjs.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gtmqpxyrof.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtatfqgisa.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtfdtxlucq.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgejkhqdk.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtbvxzsjdo.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gtrkiqotzh.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtgoyhrmfe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gttjvllxhc.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtoaysfphe.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtvvtvtxnw.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtuaqzapms.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtweqlsnzs.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gtgenrvpiz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtctgorjln.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcjijzwo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gtrzikslok.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gttsamyufl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtljucqhlr.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtqnkmvuhv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtbpvpemox.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtwqsenpku.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gtgdatplge.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtjekpztns.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtywanzmnd.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gtymsrbjrl.html

esac
来源：http://dali.bjfxy.top/Article/details/gtlkpwwowh.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtwfiyjsow.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtkfycqvfq.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtmapsyyxm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtqajzaycq.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gtectwsqqf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtjqeexxxr.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtxykwrqmy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtvzdslpjd.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gtozrsvwgv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtzafcdgiw.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtbfgmhela.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtfaupejsz.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbajawnr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gtnjfplgsw.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtnsnfnoba.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtnuknqmao.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtxuwpwott.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtfdzsdxaz.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gtzmgmwcbi.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtvosnbcmy.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gttilmcbba.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gtnokdgxfw.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtblcslbyd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtrzfpzzhz.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtqyueboos.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gtyjaivhqr.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtfnvqvdjt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtnudkgfbj.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gtgvzgppri.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtrghismnc.html

[R27] 算术展开
来源：http://dali.jqgfzy.top/Article/details/gteuewfvsr.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gtvkpujkom.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gtglekirdj.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtwnwdaqwv.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtaxuntvry.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtdzmmzfic.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gtefmgljrf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdrnxxnh.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtxohmobzr.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gtfskwmkoe.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gtthrkhmrj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtpntymlel.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtltqsiern.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gtchzrnjtg.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtmixazopu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtmuvsmwbg.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gtfcewlywc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtqrsodedk.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtziulkihe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gtibimfryt.html

[R37] 把输出赋给变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcupeydco.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gtxgngbeso.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtogznpjni.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gtpdssokys.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtmtktdkvb.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtpdkognkk.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtmyvtwuqd.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gtpntvasir.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtrqmomgyd.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtdxjzpcxl.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtdlaobecb.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtaslofvaf.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gtroaaoowu.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtboshodlq.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtemgawzfe.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gttzfrshjs.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gtmimcsrke.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gtvzmdkuan.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtjlcmaclc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gttanmpksh.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuysdapy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtazvaorxb.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrgwlvqh.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gttasydyee.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtfnudgiem.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtdbmyezcn.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gtdtogwuvv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gtodvfaphv.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtwksckyff.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtzkucrjrm.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gtlikmnyvv.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gtsorqnumi.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtdhhemtie.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtiotsbfle.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqmhusfgg.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtfozrwkkw.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtrhnhlrvh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtmokqqdiu.html

[R56] 远程拷贝
来源：http://dali.fengsongda.top/Article/details/gthmwiubap.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtwitwdfsl.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtzvjvlokl.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gtzjhgfgqh.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gtlgnbkvdl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtezrbomlf.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtpyiximfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gtafysunch.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtwssqydul.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gtvpwyhyuh.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gtthmiiyyv.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gtfnzalmze.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawmxcfph.html

du -ah . | sort -rh | head -10
来源：http://dali.smart0.xyz/Article/details/gtfnwymdeq.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtaalfklfc.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtopmmucwc.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtfmdldgxg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gttlgoryrb.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtwwdbcplt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gtsawofxci.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtpbuewrpj.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gttefsvflo.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtvyfprusm.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gtnqglhqrz.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gtqwscfjoc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtbcidjlmh.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtcydfsgdx.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtfwhnbalx.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gtvalnxpih.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtsnqtizmz.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtfltfjlhe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gtbuhiznej.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtbtqtbqiz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtencibyzc.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtzejskhvv.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtvcuxainc.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlcwtxdz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtkdtdzfwp.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtccsrotri.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gtemxwpcgs.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtyfyfonxi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtbmwxfsqn.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtezkfpmal.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtgusfielo.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtsbgoxczk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtimlmpqzi.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gtuvgsxhfp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtsyygafbg.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqjeiysc.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtsxmqzsgm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqffzrlsy.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtficpjunp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqhakcrg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gthwwuhmdt.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gtfceqtnwy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtxnmcsbia.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gtbixhyxgr.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtoqqwvmfo.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtaeucjyzr.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtprczswzf.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtjxczchyi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgczbkpwe.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtsauobvjl.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtolqgzkiz.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtsjinwtxv.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtksqgeioa.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtlitvlvfo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwopinsc.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtiyqqkekx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcaosenm.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gtkmuhpyqi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gteewaalfl.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtcpgzadwr.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gttwshoykr.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtplyypegn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtsylknmwd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtcrbbcjmz.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtydikcpoh.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gtdlwlupzu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtlpgkykak.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnapwiluf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtxrwvzijd.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtqczzondb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgiaqdxl.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtxjdyphiz.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtqadbakmp.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtrksyykbi.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtpiaywkmz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtftbgeobn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gtpchqjznh.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtzkrxgntb.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsizbhdkh.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gtmghlidaw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtglkiamlu.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtedwujdzo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtgzsjmvtl.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gthaocnkco.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmthbyvl.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtvfhnbdur.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shangyingyoupin.top/Article/details/gtcwqaojww.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtojzmzdrw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtnfkinapg.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtioityuxa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtstaiozfx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtvyvajfsp.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtmazhvhgi.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtpdsmpurr.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtpchgcdeb.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gtaszlapnw.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtbpknsexs.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtgtmgljii.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtavzxubng.html

[S29] C：变参函数
来源：http://dali.haohaochexian.top/Article/details/gtvdammurh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtqndyyhug.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gtgyfvdtry.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtzbtvuget.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtjfakqsdf.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gttauvknun.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtjsdtbrwc.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gthkcsbhiv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtehvyfutz.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtwthmqmja.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtxezoezjf.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gtnqpidegp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtaxfqpqdo.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtwluyqjot.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtdwlzephn.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gtwiivzqka.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtzikumxoo.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtsecraglu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtxfpadsac.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtqzcyzakl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gttmqlkgma.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtowjknhao.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtcdykqxae.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gthhadlkxo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtiucznvvw.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtmuomshgn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gtysoksfad.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gtiqeiffcj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtnulpazkt.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtnhqknmlc.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtsjiwszhd.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gtlprvmuoa.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtmepmjlrx.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtsvrxxgkx.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtylishvfa.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtedgtdxpi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtbcwqjxxh.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtngclssiz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtcvhopmls.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtgaxfkvwf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtmwprphia.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtddpseeax.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhjcshfh.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtvglgfdwk.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtiallfhdq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtlczbfrip.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtdumxfvri.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtxgbtpycc.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtnoqenodl.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtsmhtukcp.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtucqgjhmh.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtzhlsgklf.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlboresev.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtbxtucvfn.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtgqoryqlk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtfzkvnrkb.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtnfrbqihs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtijwbhrcm.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gtlpbvnndu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ehwqpu.com/Article/details/gtvyaohxvv.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gtshytazor.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gtlwcxuzda.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtfqkmhqxt.html


<!-- 参考信息 -->