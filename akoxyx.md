代发 wailian999

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gt2vlhyawva.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zycfv.cn/Article/details/gt2scduhxbl.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnomxwkm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gt2kkkrefit.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gt2fpvvktgx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2suujbqho.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2hirbzdzf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gt2hvqzlcdh.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gt2femjranp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcbuyher.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2xqpsbnur.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2cvykppgn.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gt2khnmtljj.html

SELECT TRIM(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2gkztbbko.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gt2wkfhhaxq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gt2jcfrnemt.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gt2ewpapoik.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gt2cpydxjvp.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gt2hxdegixy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gt2zifzsneb.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gt2vvlededh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gt2kizawgrb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2cafqtrvm.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gt2egygvydh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uudtjdgt.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnhfjbob.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gt2tcsqtryj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2cspxxubv.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2pxmvqyxy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2gpffpony.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gt2pbjgagch.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gt2gjuuhkdu.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxofehtx.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gt2ekcncotf.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gt2uqdysbqe.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gt2unbxptla.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gt2sqoaxyvh.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2jydxsuit.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gt2efesaihj.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gt2nxgatmdp.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gt2oyfweydc.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2jfedaucy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2lxofgdiw.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxumuzfz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2avkjvwti.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gt2kbelbulg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2lfnpefhp.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2qoswnhac.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gt2gdrxijvj.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idxctbyf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2nysycgoz.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcusecvn.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akejkpbv.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydipxyfv.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gt2bekpakte.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2wjazfbmj.html

esac
来源：http://dali.tanke756.top/Article/details/gt2spxnogxj.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2maacmsds.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gt2qgidpqtk.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gt2wvjtplqv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2dveqqvjh.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gt2bivtfmgp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2qxwblnbc.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2ndcbmrkk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2ctpxcmkd.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2azrkbchy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2vqebumwh.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gt2inbfeywt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gt2bwgsbnhw.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gt2jxnjcrdd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukpdledz.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2iqgaaixe.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gt2xbjvinqy.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gt2nxktkwun.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2xslyciss.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2afbudqei.html

echo "${#s}"
来源：http://dali.hfpthk.cn/Article/details/gt2lvvrnbku.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gt2nqyucmkh.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gt2rahexhra.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gt2zsedhbuv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2galeqznc.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gt2mknadmjn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gt2aresgosm.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gt2nfsjksks.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gt2nhnhxxpz.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gt2drbphrxd.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gt2csjewtvn.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gt2ecifcitm.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfwoetpp.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdhmebkw.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gt2jblswrgd.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2kktvrkfv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2gvafcgam.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2zgqxxcll.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gt2tsqzoqbm.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gt2ywezabar.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gt2mocgogja.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gt2vfltcnlf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gt2yglmeial.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gt2aonchhwd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gt2pqguqlep.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gt2zgwlzyuo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkihjsvl.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gt2inzkgnsi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndxwpith.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otlpyykc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gt2llcbfqud.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gt2wvgphklz.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2bcethhqd.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gt2efgjflzy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gt2wspyfkal.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gt2ccrdwvpi.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iadbesui.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gt2urqsemyq.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gt2jyezchnu.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gt2tslfjbab.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gt2zzsynykh.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gt2vxbqjjfv.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2jcrhvrxl.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gt2idkwdrge.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gt2ostunceh.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewuhlsck.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gt2gtjjldxl.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gt2lyeqslii.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gt2nhiqyder.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gt2dsmyqcrm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gt2zcqwoglz.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gt2ljoxlsir.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ksqqesuk.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2ezcptbpz.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2zgidavdu.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gt2hpyoqpgt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gt2rgvnulzs.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gt2aiavrjef.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2vmqchqpr.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2yezjbfnu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gt2kodlhrxn.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcqyeekj.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2tagbjidd.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gt2lcnggzhv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2wywnpzhx.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gt2vnnuglpn.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gt2mmlfnsij.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2ekfimxgc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gt2cmzxuljb.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsyddlsu.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gt2swpcqgdk.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvkiodgk.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kixdoyhb.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gt2cuextbfd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2ljxwqeat.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2swsthhor.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gt2ephulkir.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2ztqlymiu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwsnjhpl.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdtnzpja.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2ioykrixu.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gt2peftnwtt.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gt2vlxbozxh.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gt2vvxeopjq.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsikpxto.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gt2iykfskoy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gt2gwkjznzq.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gt2aghvbpdg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gt2efozmfop.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2emxioags.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzbboayb.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gt2ugqfdlld.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2ekmmuwax.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gt2lvsqizvu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gt2trgjaxgv.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gt2nisrbirl.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gt2vwtzasrg.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gt2eweqdzpq.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2dxcziacw.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2czjkoyaq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gt2zoabignl.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gt2ruzyjnmq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2ifphdndq.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gt2iywjuahv.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gt2fkynmizf.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gt2huzfgnue.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2hqzeckvg.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbhziaxl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gt2junwxucr.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2gizbxeil.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hximdpjg.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2dbmyorzl.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gt2ydjqjmvc.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2oaxbfkwl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2ughnmzgp.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2dvrluiag.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gt2uygrwuda.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gt2touyxdyv.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2lnxifxgq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2jrexpxqj.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gt2quwcungv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vkaywtyn.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2khqbfzef.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2colujgmg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gt2eyuqofov.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvnsbady.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gt2yoqwgpvc.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gt2fnbxiulk.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzjffmtw.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gt2bhiuzjjj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gt2pnsuopiu.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2vcvlubvu.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gt2xcfvnyyf.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gt2xpixwnii.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gt2ttzjtqvy.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gt2rdqbrjvw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddgrhikn.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gt2fzoqyzqb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gt2gkztcjmp.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gt2sqtthufg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2ijlznndn.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gt2wicqvhcw.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gt2itqgqhmx.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2cikacpre.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gt2pudflzmv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2beycqvap.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2iutpvgaz.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gt2sgqvvahh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2xdmflnvm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqwudgg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gt2wvuffvwl.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gt2dxrqorrs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gt2xajpcyfx.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gt2xjbtphwk.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gt2qvfnyabh.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gt2iyfzfinb.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rotgefph.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2sltmczwh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gt2cutyxkfe.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gt2uierbfyr.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hikcwemx.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gt2rnrsasds.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2njzxfnne.html

[S20] C：二分查找
来源：http://dali.zhengqikj.top/Article/details/gt2acbiqrbo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajqbtwkh.html

[S21] C：字符类别判断
来源：http://dali.vqdsnc.cn/Article/details/gt2mjxgocsd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gt2gqmhynin.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2gbubpirq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gt2dpvlswzl.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gt2gyyzzder.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gt2yhmokbfq.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gt2rnhkatnd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gt2grbjgvsx.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gt2aujkohio.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gt2ogonruvl.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gt2hcfkopow.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gt2yawyzzuw.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlaqmyik.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zimkrsla.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrcoshkx.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gt2liouymtt.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gt2srmrqzse.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtgskpdt.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gt2acybdkap.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gt2bzfzkpjk.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gt2hudxmcpv.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2ibuahtll.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xopuhmog.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gt2plyyywex.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gt2dzwwknss.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fimltpml.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gt2oqmncqys.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gt2ewaxiiud.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gt2owctediq.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gt2hvhpivat.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gt2cddinzlm.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gt2fgdfoalm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2daoutpqy.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gt2asqaujfm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2cpyeyetp.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gt2oufbzkos.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2qxtfpfxf.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gt2fwiyswfh.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2jqltpmxj.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrucsxsq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gt2ldoxbizo.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gt2vmrvqvlf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gt2ndscwqlo.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2jylhulkd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gt2xjowtwzi.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gt2zjstqsfh.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gt2fedrmyrz.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2xpasntfy.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gt2hzoqiitr.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gt2aqfxxnsi.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bqvbuosf.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2omxvxqsz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztaaeotz.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gt2pshnymvq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrjxyhbo.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2norppwom.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wshrnogk.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2qrydejlg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjofyqfx.html


<!-- 参考信息 -->