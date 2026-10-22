代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gt2jumcgssz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gt2rrghceiu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcedqthr.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgzogeyy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gt2oikkebfu.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gt2zxpkxpgx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gt2ykomlnmd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2yzrqsxtv.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gt2keazddrm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qktgdnxt.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2catnfrcz.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gt2wnjuffrn.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gt2gmqjrbxj.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gt2nxwkrvyo.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gt2vzwkdske.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gt2urmfmzbv.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gt2gqmdykcl.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2deeifgrh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2deugpfxd.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gt2ldwgvwbf.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppnxdefy.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gt2xgljfoqf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gt2zmtncoow.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujgeldhy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2umunthfk.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuizqqfb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gt2bchwzbsn.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2ijjozxsg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drrciajj.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gt2zqwprshy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdlbxxds.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gt2povulqwp.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gt2mzkpkarv.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gt2vlxbgfir.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2vymsqplp.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gt2yxdqngcn.html

esac
来源：http://dali.ybcxt.top/Article/details/gt2xrzuocgy.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsnwsohu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gt2ktscrjtw.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gt2kfknqbnq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2tfhrvqzb.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujbeutpd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2bmqhxbgn.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2svhgbzgs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gt2rcybxqzb.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gt2tgjltzkw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ifafdqhw.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gt2nctgbjjs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gt2pnoycdhn.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gt2ndhemsvq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gt2lsavsbfz.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdzxlyno.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gt2ggybuwbx.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gt2kuggvnzr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2tjuugxty.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2enmgfngo.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxipngxo.html

[R22] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gt2zjrfpvvg.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gt2nfxaaobi.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2ajkluehi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2kersltju.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2bsphlztl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfaorsaj.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gt2dtlbktpk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2ljjuezyt.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gt2eqdfugor.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gt2tehqwqmj.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2evrjjmij.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gt2xsleqavs.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2xpkgxkqu.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gt2iyuezjqy.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2igjmneui.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gt2trqpnbxu.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvssgetv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gt2cwapvzzz.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gt2ddimtffh.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gt2nlcgwixf.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gt2onfqawoo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2zblzvbok.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2olqnkils.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gt2nyihgfks.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gt2yerqxlts.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gt2ihiwwkll.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twihjmqi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gt2kmegvftd.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gt2mtekhttn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gt2phpgzuyl.html

[R37] 把输出赋给变量
来源：http://dali.yj202588.top/Article/details/gt2japfozgx.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2mgyuivxk.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gt2yhnbozrs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2urhezfqz.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gt2ecqkwuys.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gt2kcxmebjz.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gt2cuibnzkr.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qirpebyd.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gt2pjhfccrd.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2zqpzntpy.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gt2gjvkjgxq.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2shbqtpyn.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gt2hljpruyl.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gt2aimxmtjy.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gt2xygygowz.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2gcqoabkk.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gt2avuorwif.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gt2nhamvxxf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2klbgxcff.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gt2fanaddot.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gt2ckalpekv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2ybvfiwmg.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gt2rdstkiyl.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2mhvixkwt.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2uimhkico.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2xbglghnf.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gt2ldhxfotq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqzrtglm.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gt2ddjphdhs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gt2hojopkcj.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gt2azybppac.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2ymvffevu.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gt2hoqeyixs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gt2pndrpjle.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2xrafajak.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2uqjsgxus.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gt2yyfqyjbc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gt2aclfljtm.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gt2hemggpoa.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gt2yiomwtvs.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gt2obiejeka.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gt2mjjbwlfo.html

[R58] 下载文件
来源：http://dali.zycfv.cn/Article/details/gt2yfazyosu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gt2qeamynvv.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2laaugjko.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcmfubwy.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2tgygaqpw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2amndqnih.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gt2duugxyoq.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gt2zgvxbpqk.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gt2kytyyvpa.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guoaujqh.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gt2zafjnezz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gt2fkkbcvrb.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2pxysqwji.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gt2lebvepst.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gt2qtmwclso.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gt2kptyrehx.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2lawqulxj.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gt2gsfuhngm.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gt2vhlqjoyt.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gt2rnnnhatn.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gt2twdljboh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2lpcsfvgs.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gt2rrxqqfgl.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gt2rrppebkw.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gt2gkrvlwmb.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gt2amtoegiv.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2vazddjyq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gt2epstouoc.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2wvxudkgz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gt2vgetghwx.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gt2kcsxtihw.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gt2mixvgmuv.html

[R74] 批量重命名
来源：http://dali.yj202588.top/Article/details/gt2ecbrfsqn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gt2kgezjloh.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2vzvhplwa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gt2fbbevhiz.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gt2vzjynopk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gt2yzketdmq.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gt2bdbylxej.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2bufqemmz.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gt2oigaqrnk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gt2fpljzuqj.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfgodlca.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gt2kxytmpxi.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gt2ptfholhd.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gt2ssmuaaga.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2vcxyugxk.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2gazytqcx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2dkbqedys.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2agownrvv.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gt2burckyzx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gt2wgtlgmje.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2jvsybsvl.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2wrrbaeab.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gt2dxplbmps.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gt2esaneirw.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gt2bbdpmlwm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2mckwazab.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gt2momukmcb.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2kmkoniot.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2sjzlrybt.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lfmzcvit.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gt2mntuhkar.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gt2wmwxhfew.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gt2qawqwere.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gt2iajgbfxf.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gt2qhybwojq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eadyswug.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gt2saqhjaee.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gt2gretzfov.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2fttvdxuf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gt2mljjeetk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2wduzjkca.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2vkvwbbtj.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2icriqdky.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2uklcvfyp.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gt2cmiknwjz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqmaczud.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gt2mvlxxmdu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gt2rcnufuej.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2bsdumkvl.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gt2bzqkosrj.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gt2ztuqftpe.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2chklihcx.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2avazwuei.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gt2vdhgtvrk.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gt2fcihwots.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gt2wqzdmeve.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2gevabolp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2tecxqfde.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gt2nzqvtmfb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjylgyli.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gt2tuplupuf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gt2qxmjfsdb.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2bdkwqyfr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gt2ylisqawa.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gt2xdyqvflh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gt2habuiuoh.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gt2npluopei.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gt2fvtvsovb.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gt2xnjqprjo.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gt2aqqyzcpb.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gt2wybmzxoo.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcecfipd.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gt2nacrpdxn.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fngfphcs.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqxwoowm.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2vucndwea.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gt2wjrudtrh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gt2ljsibixf.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjfcdgld.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gt2dtjtevlt.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtjuczye.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2qlsknylw.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2cmwzvgst.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gt2bcraypbh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gt2jdvoleqq.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gt2zapceoub.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gt2okmjnxok.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gt2mpptyftf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqbfdgcb.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gt2kzxzvssn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gt2vkuvtapq.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gt2tihklhnk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2xxnyjqoo.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2zjxbgeqw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2qkwlfwnc.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gt2lzhqselu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gt2wqathvly.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gt2kwqnqrnk.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gt2gbcpttzc.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gt2ortidmod.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gt2uvazzbgr.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gt2zroemoqn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2lofgatov.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gt2sasuonqd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gt2acyptvii.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzfccojp.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gt2embewgkb.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gt2kdnttztk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gt2ejccualn.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gt2ueaudgwb.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gt2duntlikf.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gt2vlovejnj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2tspjxmhf.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xidrevco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gt2jspvukzr.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gt2gqsqbgcu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2ulwoazwy.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2sshpssdb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gt2ophcwbnn.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gt2hwvtjlmx.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qddfzjkb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2jkswacfi.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xaxikmny.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lguefhot.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdgqsbxw.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gt2xgjnodez.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unaokxli.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gt2veorhfio.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gt2svalatiy.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gt2gnixaqvk.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gt2uthbdxrj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gt2habwrhwf.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gt2anxseckr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gt2szkrecmd.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gt2jtbhispd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gt2aaqxoqki.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gt2zenzikkc.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2czurpnse.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gt2xqgiqkam.html


<!-- 参考信息 -->