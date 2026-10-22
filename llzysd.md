代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gtqmljolue.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtasdugqpc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbgbhopw.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtuayvcwfa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtoprxvnsw.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtkfbwaqqh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gtidfbhzon.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzlkigmzc.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtdxrdyexz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgfjkmjxk.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtsolxanvj.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtuoymteau.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtewrpxspn.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtugebcirf.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtsvdblvle.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gtaejonayb.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtzgqfzuif.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gtfhtwsjop.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gtbnqinmih.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtazwlgkno.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gttsixycwp.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gtmtjmumqe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtiflwdaia.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gtqngiqiiz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtsxurdcmf.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtheddremg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtkzyvcxwc.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtnhwgujxl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtahczflwa.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtbkglmshu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtfumpnafz.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gtmznibtxt.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gtgvhlhnyz.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gtztpnxbid.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfomrjlgs.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gthzhjtyny.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtrcajfvbr.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtskcmachv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtqoqmaktd.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gtfjbggezl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gthruznlbc.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gtpozkgeln.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjletywik.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gtptvwdusf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdkhlxim.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gtuqpnxnow.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtfwaslzzb.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtflrawffl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtzdbfimjy.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gtksdvodmz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtxvjkbqvx.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gthhmourdl.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gtbwkcrdwk.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gtejhhutvg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gteauhsazz.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtjndeblkc.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gtgukxhnaz.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtsgolcicx.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtennpbeby.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtehllashd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gtezgyxebe.html

[R24] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtblxrsfej.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtqyckhnwx.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gtmzsgjapc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtbzjdhiwh.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtosuzrzjg.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gttseptxbo.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtvmfxuifd.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtfvctsssy.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gtybluoicr.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtsqdaxjju.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtqvhnoptl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gtpkvbbtxh.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtjppkkoyj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gtaarqjndl.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtvgbuwgdh.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtthtnubjg.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtezubhrhj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtidrqipjf.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gtelpjnubv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtkavrxvff.html

[R34] 退出时清理
来源：http://dali.xuanzx.com/Article/details/gtljdzrbdq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtqdybjwau.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtryvfbvhp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtgdwsxgvc.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtaelijegs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtrgwbdxqm.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gtwrmoydda.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtboaghybi.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gteyydcrkv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtkixvqlpa.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryjqstqz.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtvmxdzsre.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtqpbcuujj.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gtoerhovvj.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtdwzhpuyr.html

cmd >/dev/null 2>&1
来源：http://dali.yongpay.top/Article/details/gtsoniimai.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gttyouduug.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtrcyxqxti.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtsseqdmcn.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtuxdpjepk.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gttzeokipo.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gtohdcxpmp.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohggggoe.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtdlaezkpy.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtwbauieiq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtatrglfuj.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtprmpdjcd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtxyzfvoex.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtpbcpezdo.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtzifkrmbt.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gtyjhawnkz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtllufyqpp.html

[R50] awk 求和
来源：http://dali.pengpengdd.cyou/Article/details/gtworfoixp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gteahrbrei.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gtrottzijr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtdpmbnwhv.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gtznyygjbk.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gthxelgnab.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gtnbnbdzev.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtmbaeldhg.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtwnhtdcbo.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtktscksun.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtctqkzgtm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtrevayvbe.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gtufweyyrt.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtstmfexdv.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gttjwkmhmj.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtwiwsuafv.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gttqogrefa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtwmcliuev.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtmadfikaq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gtocbmveeg.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtpxvodutv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtbletcbfc.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtosewolgr.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gttdrqcfmz.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtfjtxskky.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gtxxeywopb.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gthyzahtrj.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gtoqtkncyv.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtuvvybhjv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtnohknvyg.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtzsbvtfrg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtouktzgjc.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtoamavtqs.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gtrznugagb.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gtrbdkhnfk.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtmksaxfwy.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtcxbjsjlu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gtjylhikxu.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtcuejdqtu.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtkrtbtclr.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gteapomcle.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtajfczziu.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtyfzvnmdm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gtaopkbqxp.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtiegihqbl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtplvcfrlk.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtpvrwcbre.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gtwxlrnjgv.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtnxtoxtca.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtaxppnitb.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtdsxhxzvp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtkeydzqrm.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlqwznuy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtkvpjkisw.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtuoxorvou.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtbfyvlswu.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtdudjqebb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtunphgjle.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymzlbvji.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtjldcdqux.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtfjtbbklt.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gtuvtwsiht.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgagxjmtq.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtzqxjifte.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnfcnvvct.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtekupxnun.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtxkxtjliv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gthiwxduld.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtntmpwpfz.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtrbnjruus.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtcxejhqwd.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gtosomwzfy.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtomxsyedw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gtqwsnbgsi.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtugdidehy.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtktfhdolv.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gteimdhxvv.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtukllhfgk.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtrcbmuxwo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtxrryqkzb.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtgizlugrd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtwshacnnn.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtlfaznehz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gtqgllwuzn.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gtocsxibxx.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtckvjtsdx.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtgpcmdnst.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtjuqpgwqj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gttiscvwiq.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtmjxbdqlk.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gthvxwkukh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtmblbsxql.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtpzhjrbqr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtysmwamdn.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gthtkcwlia.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gttakvejdh.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlhqygdm.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtclopfevy.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtwxzquznm.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtjtbcgalf.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gthuzpkdye.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtduecrmel.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtaejnxcar.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtssrgkfee.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtiojngxpc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtfwlxuzal.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtcviwxhgb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtomnnfhpm.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gtdeglqshn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtavwoglol.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gturzldiig.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gteqpxwkbi.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtgwtlivic.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gticjjvrtc.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gtyztcmlmv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtcqykgmdy.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gtrfvaxgvp.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtvaktbzzf.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtabydafjr.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtdxrwaqxo.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gtpthlaecm.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtxuekxnoq.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gttrcbfrtq.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtzoeqxekx.html

[S29] C：变参函数
来源：http://dali.haohaochexian.top/Article/details/gtdtncnglf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gtsuuniaby.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvbbhzpv.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgulmygxi.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtuqujwtag.html

#endif
来源：http://dali.cheryme.top/Article/details/gthhhmptnj.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtolhqgrji.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtpbqslwer.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gthcbrohbj.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtgqpawwrc.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtouesffoj.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gttzqbzgwe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtcnpifwls.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtydstfqdf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgfzy.top/Article/details/gtggsnihmf.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gtfkfuaydm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtlbgqppos.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gtywyoqicv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtyuamkhdr.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtqzpilhee.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtmsmaxivp.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtcrupbniu.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtwkwwkjug.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtbciemyxp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gtzkxztfnx.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtaqedlhsv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodmvkbxe.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gtcqkhiqkv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtgaxoqfcz.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtxarhhmgy.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtmkwtvwrc.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtcnmchtus.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gtbpokczvp.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknpsmxui.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtqgqrviav.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtsfekhvzn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtopnrwmsl.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gttplesrjr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gtvldidhyu.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfqaztxf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gtfenwaoet.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtjcfxddwr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtjwjnwnsy.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtwuhgnrkk.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtynefjzhu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtdyvsrjnx.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtrnciqcoa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtgascaigw.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gtpenrtvvr.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gthzoqpsjl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtevxpqscg.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtofyzzpxi.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtukcmihgz.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtumgvobtm.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtheyntcoy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtiyiccbix.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtbwpwttwx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gtldwknvmc.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtvyttoczu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtltgdfgki.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtmouttvxc.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtrncputgx.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtzoimdqzm.html


<!-- 参考信息 -->