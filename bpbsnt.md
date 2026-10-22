代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gt2mijtliqr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gt2cssfvkui.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngfupuqe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cqqwz.cn/Article/details/gt2yliodokd.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gt2pnmkxuam.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gt2anpwbuvk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2eshtjmih.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gt2uupullwr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2pwlgjnhh.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gt2kmdtnmlv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gt2qmdhzbvl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2aiwospry.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gt2mmjqjddi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2adfoyifc.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gt2ubzcmfne.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gt2buyftqoj.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gt2fmxssdjv.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gt2tyuuxaki.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gt2houvzdxg.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2tlbeibon.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gt2igsigvop.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gt2fhsxpdbk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gt2ythmihdb.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gt2ugfoxwea.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gt2cqjrehzz.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pizowhba.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2jnudfcwp.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gt2jremgftu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2nzimjxzj.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gt2kgypuzpr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwmcgedu.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gt2iilvasxn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2lktjwmmo.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gt2ucndsojx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gt2hlgcdzox.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gt2rrlkoskv.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gt2tzeqznng.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gt2cmgztqtr.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2zjtsdgma.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gt2pqwejqsy.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gt2bldyaxbs.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gt2gcpddeue.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gt2kywnicui.html

[R13] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gt2wpegshbn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2lqczphof.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gt2ocujcydr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqihdsuv.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2cydpadql.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gt2hchquwrw.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gt2dpugwsvc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2smxiieua.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gt2wnpcjuen.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gt2idtkmliv.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gt2ahtddprr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gt2vzwfjmwb.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxjboqul.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2gcmoqxkt.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2qzutfbfs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gt2svlvubyn.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2gfecwulh.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gt2geulchza.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2enfuryyu.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gt2jgztvami.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2lnszanzn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gt2nljfdloy.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2xdnotbax.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2hbcneswd.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gt2gfyshnll.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkvcahi.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hycrarlr.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gt2uiczakxv.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gt2ckqpglml.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gt2tfehgfdn.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gt2zhrouhnw.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gt2zbhpumen.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gt2tosiezan.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gt2qnrdaaok.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvbwloya.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gt2nmkroerw.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gt2gtvkmiqf.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gt2kiugfhfk.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gt2fmlrnkql.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gt2zwapbgli.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gt2ceggomwn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gt2qsjfffaw.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gt2vnqvhpfl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gt2ofejjktu.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gt2mfxncrdz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gt2uheatfor.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gt2gawdkjci.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gt2avylwwxx.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gt2akgfxito.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gt2tupyidrk.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gt2foyxhcty.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gt2cizaxbbj.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gt2zmoorxrh.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlwcdwsj.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gt2jbtkwruq.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gt2ghshauli.html

[R41] 丢弃输出
来源：http://dali.vqdsnc.cn/Article/details/gt2aujknkai.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2mivnmkag.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gt2qpphvcgx.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2wkuhfzgc.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gt2xjpjcnle.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gt2qsbukbpw.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gt2fkypjxsq.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdmbovrs.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gt2rtldwbwl.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2mhyzqpub.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gt2dadbbxuy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gt2gvolzkzs.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gt2peajfaxt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2zxiopeov.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gt2tyttsygi.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gt2byidfoal.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gt2nferyepx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gt2oyacdmwz.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gt2krxipoji.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2fxhtdgfi.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gt2uuocqiit.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oknmvmls.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gt2yotydbpe.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2cqjudhqd.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gt2qwdaclgo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gt2vomhrvmm.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gt2klrcocyn.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gt2vcbdngmg.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gt2ovnpqxdg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gt2xekbskmc.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvfrvvsx.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktnnuaxl.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gt2jhuyyfbo.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gt2okutowrs.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2pswtjcjz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gt2slstxigl.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2rsnunjzr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gt2yafmbjqj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2qheailzs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gt2vmlunrhf.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xerdmiks.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gt2krtgmxbv.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqkswqyp.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gt2nruagopt.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxotvcnr.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gt2hfarrdxy.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gt2osrwptvn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gt2ucvdiehw.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gt2atrwjtuv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gt2vdndqchh.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gt2xbcwzczq.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjuuowjw.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gt2zikqmvpy.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gt2mwqaxktt.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gt2cnwcmups.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2dldunkol.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gt2nnmgujcu.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gt2brfpzics.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gt2audjjbkt.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gt2pqbiqrud.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2dqucnptc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gt2clctfixp.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gt2tjgxtndg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmnzjwpt.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gt2caktlkcn.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gt2tbbbwbdh.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gt2uemtyszn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gt2ckzcsvar.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gt2cgiemcdp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gt2brohnucx.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ktpgetfh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2qibbsmiq.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gt2cnkhzppi.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2rhmvzyet.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gt2xyuichde.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gt2gjlkbkir.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gt2jnbfmiec.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gt2qjgwrzmk.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2xpcedjnq.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gt2xppnfepa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2cjneozlm.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gt2ntpxmdng.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2tsxsxfsr.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2zoabkgau.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flfmeizj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gt2wjipcsbd.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gt2eooclqkk.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gt2cxbdfmec.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gt2bkhtvsdq.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwtcxliy.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gt2ugdkfwzh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gt2fccrbdar.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2hdvoxmxv.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gt2igmqkclz.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2vyukzmya.html

strcmp(a, b) == 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2kslmlqqz.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gt2zdevitog.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gt2ibgmygva.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gt2ljlbpdbp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gt2zrrlejrz.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gt2rajuirzv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gt2oeobnfgd.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gt2zcuskwhp.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gt2jpmqnguz.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2amrixgpo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gt2rgocvets.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gt2micvuujs.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2ppncuqxe.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gt2heqfjbgn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2ietysihx.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gt2zscamiug.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qorqkcyk.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2vsnocgqh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gt2yfnjonbp.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2mmglqqgq.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gt2astmzzkx.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gt2ssfjlcld.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gt2apkjvavp.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2cmlhmvyv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gt2qdfvvmdx.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2muzuwszj.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gt2rvqwnohw.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gt2nbkkfrmu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2xrcrtcfg.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gt2fqpjjgux.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2heiispsh.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gt2nedisuiy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gt2xzhwxtct.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gt2updwdcwj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gt2jirbsohb.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gt2fdtysgde.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gt2dxrzwhgx.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gt2eobvbvgn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2lqbqhwex.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2spldulym.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gt2vnldisth.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gt2gfoowimr.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gt2bxkdpdmc.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gt2vhggsfyh.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2zgbcaqes.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gt2srkncegq.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gt2mpnckrpy.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gt2uouosbbc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gt2ppacwikf.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gt2qdjpdcrk.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gt2wpbgvxjw.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gt2kqpwhnwv.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2lrfktynr.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygxwxbob.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gt2iedczgqo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gekmayhh.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2fodacrsk.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzwbpuom.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gt2ycwapsvu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gt2kjfeilgc.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gt2mvphkhzz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gt2wyleocfs.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gt2qtgdrogi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxpymelk.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gt2hntcytdq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2vofxewlv.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2fkpiwsko.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gt2kbhiducq.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gt2cugjkgeh.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2auovygfe.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gt2exrjmfbl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gt2btjpfzzo.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gt2kmutzrer.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2scomakky.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gt2agisxwie.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gt2itizpdhl.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gt2ebrrrfrh.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2urjgdtpc.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gt2ecvjcicj.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gt2wdvlnuae.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gt2akfgjygr.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gt2otnbzejs.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gt2olebkdud.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gt2mbbdgqkw.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gt2gixnktir.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2kkajpzvd.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gt2smvuwthh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gt2pmljelgo.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2yehcgjrz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gt2vflikote.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gt2wtqcajtj.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2yifshnfe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsxymtyh.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gt2voemgnnt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2opznrmlq.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2fzupmdcx.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gt2lfmwopvv.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2goididxy.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2gkutfsco.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gt2enkspufx.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gt2xbxqypbw.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gt2uizusmkc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gt2kwjylkzx.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igvficgt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gt2ekgvnsfg.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gt2vfgeiefo.html


<!-- 参考信息 -->