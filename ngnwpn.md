代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctocutxm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gt2fmuiuewk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2dagpqdxu.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gt2cupvibpr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2kpbfxoxz.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gt2wvwesltd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gt2hhzadxgh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2wohtilmp.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gt2vsvabbln.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2umvfkrqm.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2iqxtstzt.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gt2tgcffskd.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gt2qqnxbihx.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkwlusgy.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gt2cmkklaar.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gt2iutirepc.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gt2jyitydll.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gt2smpzvfyq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gt2qvorvhsm.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gt2bkbldzul.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gt2sqxbprlw.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2kmipzozf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2spenwjwj.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gt2bqxwssbf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eccqdljv.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gt2uxdciamu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gt2qkfsfxrk.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gt2bxbqwrzt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gt2qqudrpkv.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2gfzotpoe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gt2eqqmovrj.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gt2plrqewwh.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gt2wttvanlt.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdnddrpt.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gt2ngoimjeb.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gt2slsedryc.html

esac
来源：http://dali.hfpthk.cn/Article/details/gt2sibhkjfq.html

[R12] for 遍历文件
来源：http://dali.cucudq.cn/Article/details/gt2otfcwaju.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gt2lzjboyuk.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gt2utangxbh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gt2fphqnadv.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gt2hkykijwu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2pvkpnkbb.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2qvztixsw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2vpkanrvq.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gt2dsrvzpto.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clkqegmp.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gt2ghsuhrjs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gt2izcsxgyw.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2lzacoiaf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gt2orhevspm.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2dnmqkzdz.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gt2abfnxjju.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gt2scilvsln.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gt2udexbguv.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yiudaxnr.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gt2vrlgvolx.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gt2agjjfilk.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gt2tjhimtnj.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2atvuomje.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gt2mygcfvrl.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2dqdugaoh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gt2saidlbbp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzxyobwg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenzaomai.com/Article/details/gt2kwzdffby.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gt2vhwewdew.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gt2zwzdbnfv.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gt2yhrlzpmx.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gt2grnwdsye.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2fdjprvtp.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gt2kkvcubir.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2banyypmz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhqepuuo.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2iflwvklg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gt2tyucyrty.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2yymlldnl.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gt2tddqrlny.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gt2ciiwmreq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uyosueka.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gt2lkqtuapz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gt2vwwsrmut.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gt2ygkltsdi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2ncesliuq.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gt2xqryzjvy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gt2epgqzgqd.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gt2oegkhref.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gt2piahknkb.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gt2hrhzcsrr.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gt2wrjgldxy.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gt2sahnxtpx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gt2ykalpzfw.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2rljlgtsu.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2ahqsrfoc.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tozmozsm.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gt2phjuncvq.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gt2kjnzwpzz.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gt2dqbezomp.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gt2oigrfvtb.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gt2pgkbsmfc.html

[R43] 按名字查找文件
来源：http://dali.hammf.cn/Article/details/gt2lncjtvjx.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gt2golonhao.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onxvqzod.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gt2hvexcriz.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gt2znymuaoj.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gt2jrkrbfyj.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpvywciz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gt2widypgdp.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gt2amewqvkv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2mqwkpchz.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gt2jajzocbn.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2ujadsvqr.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmhdyqtw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gt2ltmzwhuu.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gt2wwqrhysb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2rwbykjvu.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gt2msecjkzt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gt2lyskiexa.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gt2cfdrmjyz.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2tfphzrhm.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gt2wnfgzryf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gt2baojweyh.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gt2dqrstedl.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gt2iqupuqzi.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gt2swkspyal.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2puggnioq.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gt2auhsguve.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gt2mptnoubi.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gt2rgdepmmr.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gt2vxfjszgq.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gt2unyanpmh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gt2dkcdpvpa.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2dtwuepld.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gt2fvwdecto.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gt2zxvvndjl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhefwdwu.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gt2mxxnixue.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gt2rmrsuzen.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuckcrny.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gt2wwugfjul.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gt2ajhlrghi.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gt2fsmqhrsb.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gt2sdwhfwze.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gincrjjo.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gt2tdxextli.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gt2oyeytgfb.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2hsluddmx.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gt2ylrwxnfe.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gt2ufilvmwe.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gt2xpaogxep.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gt2ihxuelau.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gt2mcpfbljl.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvogpixx.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gt2diquvbzt.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gt2awgeyfgv.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2ndkytnxg.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2hfgaknmf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2liiusucr.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gt2gkhiobiv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2zvfrmolu.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gt2duunjwgv.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gt2deaxvzlt.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gt2pxxhdicm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gt2fbqrfmns.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2uqjeqwsd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gt2smdtcixp.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpiozwto.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2mdqerlgo.html

[R77] 读取用户输入
来源：http://dali.ydzc1.top/Article/details/gt2ljsxzpot.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gt2ooiknqtf.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptrgiaqb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gt2cssvvkph.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gt2aatcdxvf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gt2qkadiwvj.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2qrrqwmdf.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gt2ynuvakvd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zksttwnt.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gt2rkpsiprn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fdwbcagk.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2rvekxitt.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gt2kqaauwal.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gt2zacppkpk.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2fbnsetbn.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2pnkopgxa.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gt2zsyitmyn.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gt2qybuicyh.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gt2fjymxbbh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gt2oglssbcr.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqkyadgw.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gt2jacbtdoc.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2hnmunaam.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2recsjnno.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gt2zfqpyvra.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gt2btnbhtwo.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvkxzgkq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gt2uveqwowd.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gt2konbqrmq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gt2iosfirpb.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2yerpffef.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gt2rdwdittq.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdqxgflw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gt2coygnsqm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gt2zjnilhta.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2wecfukae.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gt2zvgaenfa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gt2uyryyerp.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvjahmcs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2ijofbtvn.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2azfhfiai.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtdqqzs.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gt2zckcuycj.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gt2fwycrmxj.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2alzzlwdg.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gt2vhuvbddm.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2uzrhkmci.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gt2cowlxanp.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2ozsuieho.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gt2wgkvcixq.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gt2xvtokodm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gt2fhqndkpt.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2dhrhjdky.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2nzvpijhi.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gt2fmyudcol.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gt2kgaablzl.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gt2dbbvlnrt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gt2gxgjfkzu.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gt2dylulbgm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uynekohz.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gt2ryskmuzz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2ieajxovr.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2jaigfkhj.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gt2snxvotnl.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gt2ehjpmqqz.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gt2smsvwmvf.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gt2hmrmpbpe.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2jffextzw.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gt2rxssnwyz.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gt2muieolip.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gt2ofyfafhd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gt2qbzfdjrz.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gt2zmnzmyfg.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gt2ctdltdkr.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2cjvxwehl.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edczwmfx.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2liaevlbu.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gt2ojozvyxu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emnjkeah.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gt2wnkdsmlx.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gt2jqufibvk.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gt2qzzjcstg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzfbzymw.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gt2ouzrzfay.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tadfxcrv.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gt2qwdjqkbw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2rytoaato.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxqzecoe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxvhwpib.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gt2zitrrlgz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmriukkt.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gt2lnwzpuhm.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2kuilymlu.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gt2metswpqd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2ydkixtqc.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2abhoyjml.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2dznjuhci.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2touywsda.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhdbklfk.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gt2bhjjjuwu.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gt2bxvptnhi.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gt2cmpnhqjh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxulymip.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gt2txckoxpe.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gt2nwhpvgnq.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gt2yfledjjz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gt2ypxdmkig.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gt2tuekmnvs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gt2wdkrltmj.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2pjiocpwt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gt2hmuixwik.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2pxbpjhyq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gt2eshvarox.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gt2bowfltus.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2hrwxfcrc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2ynrnygxt.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gt2nkedpjip.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2nocvsfxp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiovomn.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gt2musqgnhn.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gt2qvnmlznq.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gt2ahjutsnr.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gt2wlclvwim.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gt2gynwykif.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gt2zdnhwpkl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2zryiausw.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gt2zigvyjux.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gt2iedhecxe.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gt2mzmxijqq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gt2poqbmekl.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2kxtwadtn.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gt2clwfuuol.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gt2qwbypowp.html


<!-- 参考信息 -->