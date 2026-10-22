代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtxakfsiff.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gtpeovdiym.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtnyheuzvy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtucfmyoyv.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gttorxwoed.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtaxmcpggn.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtcjnsuaem.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtloqrlycg.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gtcfjgentf.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtqkfeavgr.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gtqpxsqhok.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gtzcdktbup.html

readonly PI=3.14
来源：http://dali.yongpay.top/Article/details/gtopgtwkhl.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtdqszkrbn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.meibo888.top/Article/details/gtigelykrz.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gtstdlrxdh.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtwfggdoyn.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gtsnqihgjo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtmvlopiyw.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtiwzvngme.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gtjnjqgflh.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtmniwkstz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtvdigwgas.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtseidvvxm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gtmqttalan.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtdvxsqnok.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gtcgtguoqo.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtcptxjxei.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gttzyulfga.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gtmohbvbqs.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtongfdjzt.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtmghknjlb.html

esac
来源：http://dali.xinyue.icu/Article/details/gttrnvvgcg.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtrclmxudv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gthoylshvb.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnnczajg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtajfqtbov.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gttnvgtrfn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gttjebwbac.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtcxykzpjj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtfizphpfk.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtflqjakzv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtvdfaaeya.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gtfeecjayq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gttjplbnoa.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gtoxpsnmpt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gtezhzxezs.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtzhoitkwn.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtlbmpqgrg.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtdenasejs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gtderyioqe.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtpqrjjpub.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gttudgihbz.html

[R22] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtvlsdqsxu.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyzmiqrk.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtysqwcvcu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gthbckqglw.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtydxbpucd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtayhuhqzk.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtyamhviqk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtvubomeex.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gtqtxwaows.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtnvzypqep.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gtinzsszsu.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtrjydomff.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gthfbychwp.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gtzdhfjrjw.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtnbxxnfau.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtwamjqdvw.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtqjpvfdkq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gtknmoiyuy.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtryovapzn.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gtqdqagjax.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gthzxjiydr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqmziuhh.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtultsiasg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmpohmlu.html

[R34] 退出时清理
来源：http://dali.svipenyu.cn/Article/details/gtktztdllc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtalanlazp.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gtvkwwhifk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gtjeilhxya.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtswbvsemk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gttmjuxogg.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtebujdtov.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtlbdshays.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gtmwdebdao.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gtsnnjxjqz.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtzjdmqcgx.html

cmd > out.log 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtpylmzpzg.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtbqnrdoky.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtbcnabnor.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeawuhvx.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtdxeezrny.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtiggdiwub.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gtipiamite.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtxhnijnki.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtrvqsnwlh.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gtjhkbrkhj.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gtulkcnsgq.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gtueornaqz.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtpexbikqa.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gteksppxgd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gtzwqtjgxe.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcsdralx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpnstuer.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtuslydbqf.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtkiktzoih.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtmlcryqvl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gtirvdsvid.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtbkazmirr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtxtlcwomy.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gtbpdszexk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtjbekqegf.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtfmhefovq.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gtlxogqrie.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtkzjgtwkx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtdyvbmgfb.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtsmtraypy.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtwhldfswl.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtgvgdmfpw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangshuangyany.cn/Article/details/gtnqsfjppk.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gtslvrbbdz.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtlvytwxxg.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtllzbpaep.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gtggdbcghh.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gthcmzryyk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtvnqvykve.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtkennglwy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtycgzpggq.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtltupzwwd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtqprlmehi.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtbbonrpmk.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gtyvxrpznu.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtnfstwnmt.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gttveonyqc.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtmtnehmqc.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtmqzjyqig.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gtvmyelqgj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gtvrzlhsdy.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtjsnrhnvo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtjrarntmr.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gtmxdzvelz.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gteqealviy.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndtkyedg.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykqilanr.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtnyepryfp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtsonlbpfg.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtbwcsljdd.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtvbukflub.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gttmbfcchf.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtorjjnivr.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtynhhfjva.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtwyqodmfe.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtzmngbdya.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtkabqhmrl.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gtdgpjyrpy.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtksgjmbwp.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmveagdxk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtzgqnrbqs.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtszhmotnl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtrequkwex.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtoeoikcdl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtgigjeaui.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtdermdidy.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtflosvvka.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtxmdodswh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtutmuzabz.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gtzzffqhcr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gthvaxvnes.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtxhxlczyt.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gtqdxyffmj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwmmqhcet.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gtkqvvxtyp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnlotafdi.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtwhpssges.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtfeogiubn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtmpfocgbc.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtvrlqgzvk.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gthdwhdngp.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gtspngeggk.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtndvuyvsf.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtrnhhgehb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangdashe.top/Article/details/gtexhvubnj.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnyalnnd.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gtzqpdckew.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtbxtwbqsc.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtzvtvxflv.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gtvqfwosmt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtkhersfed.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtjrfreayf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtmxvfmyud.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gttzfdqpgn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gtpbjapsdw.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gtlydxnnan.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtzickekqf.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtgzjqhrla.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtltjcghai.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtnomfpjhb.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtypfmtaux.html

[S12] C：写文件
来源：http://dali.cucudq.cn/Article/details/gtrlsxecag.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtqofnmglq.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gthpqowekc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtbolaqwop.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtzkvfbnep.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtbcwwqlfk.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtbfxqmsat.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtmtxciyyi.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtdfehysld.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtknatqxff.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtjckbxvno.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gtcpacisec.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtraxqeprf.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtdyugmrbx.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gtrcimgasu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtqgunrlol.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtsynvdwqx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtcftvtbqo.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtrormdnko.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gtevgpddfw.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gtzfjbtyfb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gtnenuandf.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtrcqcgrud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtybinslsh.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtrupsgpas.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gtyutbtxhl.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtnrywmlhh.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfmvppfn.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gtocskqxdu.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gtqiuhdffc.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtmddykjsz.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtikbykmrg.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gtwsrqkrua.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtdwmodwpi.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtmhjpidrw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gtzidmomfw.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtnnvpoxde.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtvuzmmcoy.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gtocfobekm.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtdynrympv.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtdpchypsp.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtwnljgzma.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gtibojavzb.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhmbfnlb.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqytsboz.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtnyxwvgdb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtyfhaembb.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gtljlhhbch.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gtskcjiflc.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gtvbjhiakt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtziwgqoxf.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtypczsdif.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtkkwsngtd.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqikytus.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtksslfbqj.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gtzmgutqzt.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtqivcvfhg.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gtcujxevon.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtevegncpq.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtvymzqrun.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gtstuetmbo.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtddydzwec.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtncaijmsm.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtwytmnlhx.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtxopdsiai.html

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gtcibdcvgh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gtxcmeuvjh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtfswmtmmq.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnttespo.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtiykdwjxx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtllajjokn.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtlzmhxaua.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtedtrmkth.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtkbbzdsrr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtzjhbimml.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtyhvamvuv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtldpromjk.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gttlgxjnoi.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtmmspjzsv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gtbqdfaiqi.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gtmgkboamd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtwqrbbsbu.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtqtksrquv.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtucdyrprn.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gtukeycsuz.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtjtmvxgtr.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gtykqelaag.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gtfougvaep.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtdaqidgys.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gthdegywlp.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtdlqwdlxj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gtjxmdmdcj.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxuhgovt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoosgrbrk.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtisvdfntq.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtmornqyyk.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtapuxrpxa.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtiqavpzny.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtdivvtxkc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtlglqjfom.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtblrazhxg.html


<!-- 参考信息 -->