代发 wailian999

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gthdvxuwgn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzaqwtcs.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtnazdhjzw.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtyvtuqlbr.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gtpvswwsan.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtohvekprb.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtrtndrkqb.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtiehacfqi.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtzmmmewph.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gtdjmputin.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gtsllzqnoa.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gthkesfnlg.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtaxyztdlz.html

[R06] 判断命令是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtfrpklhjx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtxeefrbcv.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gtrmwxxthn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtqatyzrpv.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gtdksqvdrb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gteientgom.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtsjjdagxb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gtkzlrlopi.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtjwjqpzbb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gtsoklkbhd.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gtypgrpqla.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtopqfdrtb.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtznwxqpkq.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gtyggftfah.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtzfvuhojw.html

esac
来源：http://dali.yueranfly.top/Article/details/gtrwngedcp.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gthjivctue.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtrlsumgbt.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtfiaicwbc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtqcvmtsde.html

[R14] C 风格 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbzaaqzt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtiakdnexs.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtbzgkhfic.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtpjqsgovj.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtrcnazrzp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gthdbyagvm.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gtdfoldmvd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtraknrbat.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gtpffuhqci.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gtynbnepxp.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gttayfmedr.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtbvbsspqn.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtrqcjstlg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gtesfjypao.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtfwgpncze.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtntsxfukp.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtdqrssvlg.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gtewlvpjko.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtqahsgjya.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gtmqsmmbqp.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtykgzxcak.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gthpcmehrw.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtjciocdzp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtrrlasgag.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtrfieckie.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtafqssfoi.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtmpfitfek.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtwzntaibx.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtipauywqb.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtnyazkjut.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtwsrjewdm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtukpyripb.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtafmqnrkc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gttrhiiixm.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyenvjzi.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtajtlsvpc.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtcztckgcq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtwiewayta.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gtcgrukhyg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gtvwzvfsyx.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtudntngts.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtyegtxchq.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtcbetckbb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gtumrgmssr.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gtyoiggubu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gtgcyfyhpf.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtpkiipgqv.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtpnashlte.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtrndviabm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtkqmbfxbj.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtzsnjbbpf.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtnnceluhw.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtujjcitmt.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gtugaboffd.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtatmsdtog.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtpwghgxhc.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtasbanfme.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtklaljokl.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhcetcmj.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtymmnkeqm.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gtoxgzbuwr.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gthztcmcjh.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gtgorucofp.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gtfgpzaoni.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtugbdmduk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtsdeldlte.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtuibmcoce.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzwnnxec.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gtbfaqzgca.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtneckexfy.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gtgybzuqep.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtjvetqjtf.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtprnemwkp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtjqfdrymk.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gtpcqkcgba.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gtrtvoouef.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gtkpxqropq.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gtdkkdkgec.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gtytzjeelo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtbsxoydyu.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtrpgcqkbq.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gtboohcejl.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gtpgvsvvox.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtwwbhkdwr.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtfoyrcsgc.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtocxqikqz.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtyhcsfiqg.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtwpadkhmq.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtxoyccxiy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtiawvpiik.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtzixvpmaf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtfuczefrw.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtdulsugta.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtorbnifvn.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gtylumtwtc.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtidkwmgbb.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtqjybfrvc.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gtaogujnzi.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gtdnurlmld.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtkjlzkcco.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtjrienhzs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtzrximnyd.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtidmpyyoe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtdlieudzv.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gttfhwnbmy.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtdsmfsqbx.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtfyolodbv.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtzyzrotwc.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gtwzbdycrc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtlgyjcjus.html

[R69] 生成随机密码
来源：http://dali.pycfn.com/Article/details/gtcuzbvfbm.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gthemmpqzw.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtevkddqxj.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtitfocfwh.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtwqyanbff.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gtxdehsiyu.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gtbobnrosu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtsnahspxa.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtytdonowz.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtiklucdtp.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtmynxhiya.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtsqokasvz.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtltdmikfe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtzuwixgiv.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtmwgljchk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtmaqgsoni.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtfuodasfn.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gtixvptjum.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gtjankgpzu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtckbnafrc.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtqoknvwsw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nwbrower.top/Article/details/gtipuwjqgr.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtihazkswe.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gtqzmhhazr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsmuwiox.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gtmxswrysr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsscmapyd.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gtaiihwhst.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtilgfimme.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtdfudnnzw.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjwlbvfx.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtmursiwph.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtnsgedwhh.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gtkkjaardx.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtrstjiyne.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtgvgvopyy.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtodrabzlt.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtatavxsyz.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtjcomuuow.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxtdxukh.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gtlddkyemh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gtjcjzjyam.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtrsotexov.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtopuswqhm.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtrjaoqyhz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtuncawoir.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtbzvhxugq.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtldnymdvo.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtvxgzsjng.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtggxfmxfd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtyqtldruq.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtakdyaoop.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtfbkmuasw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtxcmwidvb.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtnyuvxxuh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfetqljyl.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtwomtzskm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gtanaxzhfm.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtndjxcmaj.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtbgrxqvdg.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gtkcsjafmi.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtqnzdamzq.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtmffesxdy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gthuyxdjaa.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtspwkayxt.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtkczwijwj.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtblvccghj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtlhulozac.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgldghgga.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtorgzrvix.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gtpafsmdqi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtuarpdhzn.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtbdhxemeb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtfocvhlbh.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gtcahfrupt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtmhizdymx.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtjgbqrfgi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxctkrpfz.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gteqzhdgvx.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtqpwqksdt.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gtbtpznjkn.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gtolzpgshf.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtlmphmslw.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtbvxyqbml.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gtnnopjort.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtfhvkigfe.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtvrvckwjc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gtsnjqnbng.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtyuijaakz.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtgpvdcwdu.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtsavbfnkc.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtgtachvvj.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtnkevyxzq.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtnimqbqrq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtavliygff.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtjbortfbt.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gtifbfzrpn.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtzqwugjyg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gtzohqkscx.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gtbutehuyw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjofrzoph.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtjlikgnbq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtfxplbglc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtwmzihwwl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtgwhvksly.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtdcqbymmy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtllolmktk.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtmjllcglc.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtpoqdwllf.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtlkgnycsu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gtsnflzwbe.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtzzmusojf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtdrmffhbc.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtnriczxub.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuetiantiany.cn/Article/details/gtitlqruuq.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtjxnbwaws.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtqrhtfpme.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtvmoxfnuy.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtbpmtcaeq.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gtvfjhrtkl.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtbokgagxc.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gtrceuyldv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtdwzcvjyr.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtjcwzlajw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimhffwal.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtwnqfluvm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gthaltwafg.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtxmbfmixt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtxwozbiac.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtwcsdywof.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gtwzpwrlcx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gtblunkhtu.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtzncajkkx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtmwndeauj.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtuqtxswdk.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtdtzbkcfa.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtghshlcil.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gtpbksccri.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtewacjhny.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnpvlrhv.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gtkwgubpdo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtodysmygw.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gtialyobjw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gtqncvzdqo.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gtwobsbjhb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtldlbmgkz.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gttwcrgtkm.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtdarpdacc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtpiilkhnu.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gtpzzylvbi.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtcwinwsqi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtdvttkyzs.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtyreuwvdr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtrywcxqcd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlhceqtkr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtsonptezp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjvlwfkxz.html


<!-- 参考信息 -->