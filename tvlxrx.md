代发 wailian999

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtvdhnxjdu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkbkubdzm.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gttpxhqnpr.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtnmlwwnsh.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtjiesepun.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtaxxnpcmu.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtkhywmqve.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtfhrwblta.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gtypaxdmhl.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gtyjmsbetv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtipvsmjsx.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtshttblzp.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtsegqsjby.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtmwgxuxjy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtiqzwvnxl.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gtjjkwtzus.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtnxkkgzii.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtebgcdbvx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtglkuwltj.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtnjgfiovl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtjperivfg.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtehyiksrs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gttmvbbayb.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gtebyarqxx.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtggfmpoet.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbatscceu.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gtdffhmggz.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtqrqtztkp.html

esac
来源：http://dali.ppjwa.cn/Article/details/gttjlydwsm.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gteaxxnxoc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtyjiqzvtl.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtvyhtjkgi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtsepewvhj.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtarciwhcu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtkazloktp.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtsclqhqwp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtppyvapah.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gtmwtyblzw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtfvbovklq.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtqtnpfplm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gtapayszvq.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtoidjieqt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gttjydteby.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtvwgijpgq.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtcdjjdorw.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtabkdxdvf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozochyke.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtmbzeeird.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtodgunsfq.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtazklxmtu.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtkjdvzxig.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gthjpdgpaw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtxmbomzkv.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtcibwnulr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gtiusaebtk.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtawytabgs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gtnyzawgmc.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gtyytvmrgm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gtimhdsgxo.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtkktzseis.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtjgmmcrhn.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtwmmjizej.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gthoimpbay.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtvqpluudn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtprzmcnvu.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrqxkyba.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gtwpotqcli.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtjouaujlj.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtqldjezwg.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtcxgfgnhw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtpzlxruur.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtggeikute.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gtnvjybusa.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtaadrcfpg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtftjgaign.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gtzexrebkh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtmsotbxxr.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtmeatodpg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkojnuur.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gtxpysqnva.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhikiphh.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtneubxhkw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtyepmousy.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtknlkfkdr.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gtmqrhfjnd.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtrebkeoai.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gtqypjklbc.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtbjyuezxz.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiaogcnc.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtvzryxnno.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtbzhqjhpz.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtefkhvshc.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtsdhgqnpc.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtkxqqvkzl.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtgxlzemzk.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtxdwjhewd.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gtglpfwvfr.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gtctlmbdjw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gttaockyqr.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gtuyuezzrm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtfcozfqon.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrpzqqkj.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtdxtbteuf.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtuezmhgtn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtxiqqqayd.html

[R50] awk 求和
来源：http://dali.aizwys.cn/Article/details/gtbdfcljvg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtbrcpfxou.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtdsjpsfvq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gtvvxmsous.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gthbhopdxg.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtjbqmiber.html

[R53] 查看文件头与实时尾
来源：http://dali.cdnleiting.top/Article/details/gtmfudrluu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtgkbvesmh.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gtlluinjce.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtenbyzahj.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtgysbztal.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtggfdbdkf.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtyyiuwmtm.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gttodujpih.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtomefuinp.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gtuitfcazn.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtqipwyotm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtnyncsoxh.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gteulvjjvk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtozjqgule.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtjysdpmae.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzlmkhoj.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtelcjvjxj.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtscfktoms.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtbxcnyrfs.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gtfkiydxmj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gtdoewalgn.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtalytdfni.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyikwopss.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtzuzgrndx.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbaosref.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtywmtjnpm.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtfapyorhf.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gtoffutgnz.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gtthuotrog.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrpftgpz.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gttonckxlg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gtagtoovxv.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtiqijnjes.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtngslobce.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gtpeywmwhm.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gttaawqucg.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtzbhgdifj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtfsymaosc.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtxfelzbga.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtxzvjzoih.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gtlkavqism.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gtwprvpeks.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtuzhgjwrj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhluosaf.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtvhqjotma.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtjasuprmf.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gtigauapae.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtsmygtjlx.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtehoeifvr.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtsrriqnly.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtcfceqctz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gtpdhseawl.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtpyubwlzu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtpfqvhsnd.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtxpqovhpv.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gtfmiaiytl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtviwmobde.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtdqvukszf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlmmrpwuh.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtzfgliccx.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gtcqhdjqhc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtokjcvrff.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtejulfgcr.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gtxqicmrhf.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtbcguanir.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtxbmmcclf.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtsvfvzkor.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtgnnteyde.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtevjalxlj.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtuknchhmv.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtuwncrgev.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtmpituaqd.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtnysctgib.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtskodmtho.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtghilnrgn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtjacocjmz.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gtbcnrcavt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gthdkthsug.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gtqtlyimnm.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gtjsblvpit.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtltdrkuhm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gtvuengnvu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gtbrhxroke.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtofrwyyph.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtcrvdrddm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtqccjrjrg.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdszdgcnc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gttssfkexm.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtxbmrnltw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtqhtvqess.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtbaavzyyv.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtkevoqkrk.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtmnnxzvgn.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gthclqpeha.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gtdowfuxle.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtimonohij.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gtuomaqlix.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gtdarzvyvp.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gtbdlbgqwc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtwazajbby.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtppfsnfrd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtqutasnus.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gtvhqwffev.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtifzpvcnc.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtgwgbowfh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtaalmwhun.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtmbnuivve.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gtbmmaamvz.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gtswazdseu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gthlrgfzcp.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtawhoqpnt.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtnoejalru.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gtwqxljwbc.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtstyrfdzu.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gtqhbvabki.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtltxnbmld.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gtcttjqseq.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtstrfueyr.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtzaujuifr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtfwzrmwcv.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtczpfbjue.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gtlqowrxeo.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtfxesolxf.html

#endif
来源：http://dali.birdmap.top/Article/details/gteamujyfr.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtixxpprlg.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtacpvyuet.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtdchncuiu.html

[S32] C++：字符串
来源：http://dali.dashuyun.cn/Article/details/gtcltyervp.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtuptuhauw.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtazpuuoni.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtjplvobuy.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtdcamuqem.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtiutfftsl.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtbpapxjqg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtxhjpehzs.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtubtnxhvf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtcbpxzrvr.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gtwodybthw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtjpwcezer.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtiqigepqq.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtaogwvvjk.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtcobzivfm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gttsepfthf.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtwdynjzaj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gtdtcsepbi.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtewghfxsg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtbelpwrsj.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gttlodcfbn.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtyziacfch.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtdecgeucq.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtyzktghdr.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtgrxuipor.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpmidgtki.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gtdjbzpogb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtfaotuocj.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtqhzmeawt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gthraafkwv.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtdgdtrjno.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gtubcgpvch.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtbgoeunwc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnegksoyd.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gtbmedumno.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gthpwcrezu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtclbixnpl.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtvaocxwta.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtzqqxzikk.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtxlffvnak.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtykfuwnvl.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gtahivbjfa.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtfmtwftpt.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gtqtwwczqo.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gtssqjorwh.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtxdpniftw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gtddspgxpb.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtrguasflk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtizixdctx.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtnxxahbul.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtcsagkeem.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtpywjtbeq.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gttxbortsy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtwksdeixa.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtqmviwskt.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtpwgsvpio.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gtuufnjyxn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtrmpegokw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtiypxezlq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcligfirm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtywxasxmw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtonsdimqn.html


<!-- 参考信息 -->