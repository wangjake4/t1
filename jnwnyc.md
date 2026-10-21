代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtjfojxjee.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtwkyqxfqq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtdxjqgykv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgdequenq.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtljtsqpdu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdidreugn.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gtcffdusqb.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtxepihiyd.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtvnbuxksi.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtziofrogu.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtkbtghtwp.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtabccmdox.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtysefuptp.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gtdimgypca.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gtiqgdcqnc.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gtgwinfvfe.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gtrggzxbeg.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtudtifgbt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtkpknilwk.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtdbkvpkyc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gteyoisqkv.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gtfarymxio.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtyusawllc.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtnzyedbdq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtsclmnhvk.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaosslgr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtuzxubwvc.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtliexawph.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtudqrtimm.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtzmilcooq.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gtpdxvcgmb.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtroaqerlj.html

esac
来源：http://dali.ehwqpu.com/Article/details/gtehdjljiq.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtnnnhorzx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtfmdziwwh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtrcwwcqdo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtziijpgjr.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gtmolxuajs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtfvsogyfd.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtabnnbaal.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtsuptigok.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gtbxsfjlzh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtoddhryoy.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtodbnlxig.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtyzdhnvkj.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtomlvkixh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gthbpaeyfy.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtqaodrjob.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtuhpctiod.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gteqcmocxr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gtrsxewluf.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gtfpixkfle.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtxcexacia.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtcactsyku.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gtlcercqhi.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtknqmxfci.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtyakuswys.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtrhwyjwgl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzhhooeh.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtquyqwnaw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gttztruncz.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtfddirmcp.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gtyadlsuta.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gtymhvtzth.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtpsovicwx.html

[R28] 浮点运算
来源：http://dali.hammf.cn/Article/details/gtfafokuto.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtkruvodps.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtrnjnazzg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gtfhakzusg.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtbrfpyohr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtwgncqqvg.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtbugoquqm.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gtaiepiudb.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gtufektido.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtlprpncbj.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gtpkdieavb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gtehcdlisa.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtoxsjirbh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtywmpgbxx.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtymjjawov.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuetiantiany.cn/Article/details/gtygjboesm.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gttajxnfsz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtqhghvask.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnydtdpo.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gttmqfozio.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvqwqarb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gtxhbvmroc.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtpasaloec.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtdeigtiqj.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gtqoxikzuh.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtdwicwmpc.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtzllhdrlu.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtowbnmhzb.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gtdwxtqzwx.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtfkxrqsho.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gteniolpby.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtaiesgrij.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gtyzqoejyy.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtmdksmrxx.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gtjrdwdcvg.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gtgaiudwos.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gthkjzvsvk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtzcvgpwzu.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtguyoacdq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtmnkdyhms.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtqfujhvfe.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtrnugvdrm.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gtmwnlgbzw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxnfdmzg.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gtvtdsdjqg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtifpokwfv.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtacyqdggs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtsbsojvzr.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gtxsbffoad.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gtxzrziwbc.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gtfmltgent.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtmyadnxgc.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gteucqcwrr.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtczarmwfv.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtpoafkfvr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gtacuyoqpc.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtjhayxokl.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtozedmgyx.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gttkpdywrc.html

ssh user@host 'uptime'
来源：http://dali.chenjidiqi.icu/Article/details/gttoqcywhy.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtjgecilvv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtrxdidjzr.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gtoubtqwuw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gtswsauxvv.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtgsylhwbe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtpyeobatb.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gtiehhrrfu.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gtafknjhoo.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtmpbmpqyg.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtjglbxalx.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gtxqhgcqmp.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gtdzvbxcgg.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtenvborvc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fengsongda.top/Article/details/gtcmikqvvr.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gtqbngavkq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtzuybuwlb.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtdzlzrces.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtxrvhfnpl.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtvkwcatse.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbxkfrjo.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtfnisydlx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtadwqfwdt.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtcfsotozn.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtheismzeh.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtehghzndc.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtkjhzkqpc.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtiwcekfyq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtahovjhpr.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtvrlqwesp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtetvpkdnh.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtaduoisrn.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtttoqwwuu.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtcqrfaxxq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtiwlgmyip.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtunejtsnz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtgzbkhspf.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtdqwgzjed.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtfdkclqxr.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtaljdabfz.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gtnzybrskk.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtitnaqhnw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gtrronubuv.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtvgdnlzst.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtfomsilnx.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gteoqnzqgk.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtdzyghowy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzvgkgoym.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtfcsvxfkt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpcruhloa.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtcgyuevgp.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gtcvdqptgi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtvfhkvehu.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtdltqcbao.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtfgzhkmgi.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gtomhhvdxy.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtwsquoldl.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtcckemqqs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtuzyctkuh.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtqsuvipsi.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtddxcdjhs.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtxuipnaay.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtkyezmzkd.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtpxiiekep.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtgvhpnfes.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtwhmltekp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtsuegqkhr.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnigaslwg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtudnunx.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtomfouebk.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtkidfxixd.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtjfxqtuyr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gtkqqvaclm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtvrslfoze.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtozvxinej.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmmebkuk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtqhmdqtjg.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gtkkzktfic.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gthfsnyoqq.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gthkehrelg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtrplzlxxs.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gtracbppyw.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtjdpkphnp.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtlvxjliau.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtznjvpqag.html

[S17] C：安全拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtshztehkj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtefmtthzh.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gticvndinc.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gthzqetibn.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtkknewmla.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrahqgxs.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gtybcgudss.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtxgduhzpo.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtpirgrahn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gtsduhgfes.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtcoisivul.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtbszfqhpv.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtfvaeqsuj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtotdhxpbm.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gtzrxqennp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtmfmpkdgu.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtneldfomq.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtfabfkxjo.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvicbmdhb.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtajhsoxvr.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtrkrhbaab.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gthydiwpnk.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gtrffvdxfm.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbufpxvj.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtwsmwfjku.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtulktmrjl.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gtodeudfbh.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtizknbczn.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gtxwlbfouv.html

#endif
来源：http://dali.316326.xyz/Article/details/gtqdomoxos.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtrqezavra.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtsugfzrzb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gtevporxxz.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtpvhfgpsq.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gtrutbkqni.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gtwncoxxki.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gtujbbssti.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtrhsuuwcl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtdfdggzva.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gtqcbfqtlw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtdsjrszgl.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gtgqfohbju.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtdkndawbd.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtybgguihm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtvucvqbzw.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtxeigltaa.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtlfomcmfc.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtkrejnlsz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtdtzrujgz.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtjdnqbbdo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrvshlkz.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gtwxtxcuzn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtnilhvllt.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtpnjddcis.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtofjqijgw.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtvuubbcco.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtnffpjlqx.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtcdxslezr.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtqpzbyxad.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gtielfratp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gtctylnbhe.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtkunzpqwy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtujtyjtdk.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtavphzgtf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvnnoynr.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtgrwvyhwx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gtknglyoqe.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnosamoud.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gttbztitcq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtkdioqnpn.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtapxqunfz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtprolixqc.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtpdrvzfwb.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gtxmunmfay.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtoqflahjp.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gtcifakeya.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtiveqnijp.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gtoqiefuli.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gtbrsobzsy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtxgqkxmmn.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gttrntdyko.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsifmxkr.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gtqitkzzrt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtypibsqyp.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtntyqwqdn.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtzyclgbis.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtjybompbs.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtgumcfvfm.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtridpnrto.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtgbynepfu.html

[S60] C++：遍历并删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtfabngszl.html


<!-- 参考信息 -->