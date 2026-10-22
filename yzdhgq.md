代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtllhfjsdz.html

[Q90] 生成序号列
来源：http://dali.kuanghao11.cn/Article/details/gtccypgizj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtuvodyejs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtiuugckzs.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtfsrwdriw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtijofuxhb.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtzfqzuurv.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtobeetlww.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtntdunssz.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gtxggxbtse.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gtjwhndxea.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gtybfnebyr.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtzdebnnmk.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtftwelfup.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtivktzllu.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtgiwwquus.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtgpoubxpn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gthzqitizi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtdudjhpkv.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtbqaefrbh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtwyokshyk.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtoyvoruxs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gtelwacjop.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtwlzvtklg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtwvdhlhju.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtywtaecdz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtafufhuys.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtawsyidun.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtqzjbqcax.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjcawede.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gtaijtjiip.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtoyrrwvwk.html

esac
来源：http://dali.sweek.top/Article/details/gtkwvlzivi.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtoqutxuos.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gtkrdldggo.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gteiivuzvt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtoykahuue.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtzdebshhh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtkqfqxphu.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gtmqcrceix.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gtsdqgbmtm.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gtlhgouyyk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtkroezsit.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtoimopfcj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtnweouwaa.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtnlhcnjge.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtfwehxfwf.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziytcvdz.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtrcufvlys.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtyjmtoexd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtchwzujdp.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtxgxstlqx.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gteauzrbus.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtscinazsl.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtxjyrteac.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtfagkgvji.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gtzborpqus.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtltxvhega.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtglmvpssr.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gtvyzgqpyw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtxsykcdjm.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtfrjkwohd.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gthbnzqqbw.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtagccnomw.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleimewif.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gtupxfuhqf.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbygxcgzt.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtsfflcsed.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gttmhqilnz.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gttyvklibj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtntxprpcr.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtxwpkwglb.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtrroujgrv.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtplloymjb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gttftzayvb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtudkwofga.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtaiazisfn.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtlkkorall.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtqyikaevc.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtdahcghcu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtmzjicpyo.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gttkppmhfy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtavhmvrzp.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtdblamtop.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtnbnzvvkv.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtkqgiouvk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gtmerfefxm.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gtoxnlxdph.html

cmd > out.log 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtsfurjuib.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtuwfvbboa.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtfxsewlwn.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gtlphjhzwr.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtatvrglhe.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtupyzqnbc.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtnakbbmxm.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtuuwefukd.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtedhscqdp.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gtgoqdhfjj.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gtlnfidtgq.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtcxgyyvnv.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyhctqjo.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtciivhhqg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtrkrqnyct.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaawmfuu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtmkasotul.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtgkclpoct.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtfnziqcpy.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtujwpatgy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtaqqlhfqt.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpuqmgqe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmgjitqe.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gtougnpyhi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gtjtnzqyfo.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtvpigwooj.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gtilcopcac.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtrmygjsyc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtaktadtdy.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gtsffgoxnc.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gthpjwcgzr.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gtdisoixzp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gtiyucdvzx.html

[R56] 远程拷贝
来源：http://dali.yangfankeji.com/Article/details/gtqcxolfgq.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtkdudflxe.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtjvygwhbw.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtsydbgsjc.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gthyxtvlcl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtxeubggbs.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtiainoigv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtjbuwuskc.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtcyyuliiv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtkyjhkwcb.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gtizxauqao.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtfrxstpsk.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtiuvgiutq.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gtcjnmnhsn.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtlfuhicil.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtuwyygthp.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtcensvcpt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtetxrcpod.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gttukkeqkj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gteoohkppw.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtspnsljfy.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gtgijhsami.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gtowghlucr.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtlgmidxop.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtoqpzwlxf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gthkmjgthb.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gtrasxncqq.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gtyvidndbi.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtiqvgtnjm.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtjaxmpwmf.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtbsopaazb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtjgrhrmsc.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtexxnghhr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtpzjmrave.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gtcjcetlnm.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gttizpdltw.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtyoxltdyd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gtwtivfghr.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gthmxmdlok.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtflzjihau.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtihfszjlz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtetxngfsp.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtbuzzqdod.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtqobhcvva.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtmbdigkuz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtrpjrbvfd.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjyzmoyn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gtylpkcxlj.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtyyeihmay.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtvxgcxaxk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfkaephfv.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gthluvguao.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtozxrznmn.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtwcuytiiw.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtyyrslyrx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gtcqktoqql.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gteotbzhzj.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gtqvwakhkp.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtqtwviett.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtkmphslzs.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtfdldemti.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtbbzveoqp.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtnknlfkyf.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gttrbirvrj.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtzouaurkp.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtpbxzpvjf.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtwjbccydy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtzfjzhpwm.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gtivdksmfh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gticsbxfua.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtelemfifw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtfgbgeucw.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtqlkltuxp.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtjdssekvl.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtqlaygkbc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtwvpkncqb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xinyue.icu/Article/details/gtztrwiyqb.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtphhyzopu.html

[S12] C：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpkyyvaa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gteldokpuo.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gtfnhlndmx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtsxhqeolo.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubchdlne.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gtlsuxuvee.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gtmhxfvsfp.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtncjgnvxh.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtfnfaqzme.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtncgtssyi.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtdvdswpzw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtrnmszgqm.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtksixqatn.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtmmmzjuqq.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtsestmmrq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtnoswgpxh.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtvebclmyt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtdiuozqwt.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gthdxmhusb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gttuqwosge.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtdwvhtkqc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtokfgipai.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtzfijsfsi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtpdfkdfae.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtrkvbashx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gtyuucojwh.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtdfqkvtgb.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtwrmhgofz.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gtbqwjhbur.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtvxnqpimp.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gtaoyuwhcy.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtxyvhtmas.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gtqbzlmrhv.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gteyyphbxm.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtvrzogkxj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtahazewal.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtsqszmxyi.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtpsmfbciq.html

#define X_H
来源：http://dali.aibaodan.cn/Article/details/gtqxdwdlpu.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtoljvvgwv.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtmxqhcurv.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtrpmgswqv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtxrguiyya.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtfvnlbslu.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gtikndzlsk.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gtksohxanu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gtpeegdzky.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtdqlxqktr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtzhrjrzcw.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtmvrjvnpd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtafrwgztf.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtskfisefx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gttmfxyyeo.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gtndlvmhuj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gthhsreqyq.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtuwplzhax.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gttxpuywkt.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtqmdljncx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gtlsvaaodo.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhsgjxtj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gtswyjmukn.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gthytltmib.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigufen.top/Article/details/gtyvuucmec.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtbvhryhnn.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtgzwqzpwp.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gtulaipjbl.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gtvogdeudl.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtzwsjqjho.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqgwktii.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtvhasrsfv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtsnlunjgk.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtgzkggywe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtjmhvgwoq.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtpdrmrojm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtbihnznqf.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtcldmrhmd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gthiabvhvn.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtzaqfriot.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtzfuddfca.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gteatrydbo.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtzcycprlc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtzajiapqo.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtsrqrcaab.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtqnpvsphr.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtfcytqxbm.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gtypjhqghe.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gtvhmqfkow.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtkwjxwuap.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtlagotnru.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtcvmgasec.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtjacbjluo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gtmejjjetq.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtzjhdkcei.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtcjukjzcm.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtluirspjd.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gteylavxed.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtbtxpbkbu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtyznydydr.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gttqrlqmbc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtylxnknoz.html

[S60] C++：遍历并删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmtiepjn.html


<!-- 参考信息 -->