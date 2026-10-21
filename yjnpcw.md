代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gtlghiskty.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtqjdxpqko.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtmwuinxhr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtvrsfiuib.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtoooieiad.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gthvgjwlmb.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtbritldco.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtfntmwsta.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gtmnfcgsqz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtasrsjvph.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtzhobswne.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gtxxytxmhd.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtswbqojbc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtlffhgbab.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gthrcwgaen.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gtzwhubixa.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtyldebuwr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtxwpvsbef.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtoqaywdms.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtulejcagp.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gtigtqkqsk.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtpsqvapdb.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtzlkkaoun.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtxhhmipic.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gtifngcvxo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfiakuygi.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtqdokscwx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtmbhrbapa.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtfwgasokd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtivlormun.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtubkajbpr.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gtmgxbswva.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtcpcoodnq.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgomjwfkh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gtfwwybnxd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxqgxcalo.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtmuhgtjlr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtksnhxktj.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtgcymyuet.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtrxccvlcf.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gtfvwoekfh.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtxfmuuorv.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gtqwdrboig.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gtutcvtokf.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gtatoqypdq.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gtihgtbxmi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtmbcuojka.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gtoklyzubb.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtszhdpnjh.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gthomhtfti.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtxaewmjzo.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtonvkilbj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtmpmyzjxt.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtdxgoagce.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gtoaohgbcn.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtodmhzoik.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtcnlhinxl.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtuwqfzrki.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gthssgywlj.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtgndbgxfg.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtvvbfzeqz.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gtceoncnoq.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtighduiyq.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtvmcykipd.html

esac
来源：http://dali.jyoumei.cn/Article/details/gtsgokqawn.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gttellylrg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gttcglzisj.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtypgygmle.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtojjagkxf.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtzrksovpo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtbundlpma.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtzctaxlyv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtpwmbojng.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtzclksmxe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtilkcaint.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gtilwogjkm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtkzyjsvso.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtluxqfwwf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gtansrtwfy.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtadlymbex.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtsnodtppy.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gttjncanys.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtnmwqydat.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtmdwoaoww.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtpbypptvx.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtvapcrgmh.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtiylijjln.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gteaaojtyc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtwbzsxqxk.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtamcwjnjz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtkkfoqwyj.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtkgvghxmj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtporwrzik.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gtummjcmuw.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtjvtdoodo.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtuetoujzj.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gtkglszonc.html

[R28] 浮点运算
来源：http://dali.zhengqikj.top/Article/details/gtuojdndkg.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gtpyyidchw.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtpdieblvv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gtpamboakh.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gtlqovbmcn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtymrygvam.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gthdumwkko.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtvvlftuet.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtfrzcegzm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtbksxemyj.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gtjxyxeksy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtrotkdree.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gtthwyegux.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtxbscfxrp.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtnabowhdt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gtsmalsqjn.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gtjfmdikof.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtckdzehfs.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtunpgnbxg.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtmrbjrqry.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtnlaooqdt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gtkbkgscyn.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtppgzrvpv.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtwjpelnzh.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gtbvzwswcv.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueobyqwk.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtemurzijl.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtdkrovtqe.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvaqgyox.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gttkgnaxuc.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtynyubfxx.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtgeboraek.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtfefzfpxd.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtnfxhnwlk.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gthisunluc.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtntdizvwf.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzblkhov.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gtienfhviz.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gtvexowvaf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtdqhrcgzg.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtoqsehgah.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtusafskoc.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtokiqfxxl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtnqsbbdpr.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gtbyaboymr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtjhtfjltq.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gteuiphznt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtehhwtipe.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtwknunwnn.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtxppyshzp.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gtpifscovu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtblizulsr.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gtkfpajyxi.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gtjgoohfny.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gtfxrpxjxn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtlaufzhty.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtmnvamgqo.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtigotqnnr.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gtdaejzncx.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtbehghnyo.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gtlmramomf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtqcrndyec.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtfhcsgiad.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gthcdmtvdk.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtzaqkcwgb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigufen.top/Article/details/gtuxhutjnf.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtlbkxkajj.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtqmzjyzul.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gthfsvalxw.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtnjgwizft.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtlattgdmn.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtehdnafaw.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gtowycjfkk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gteeotbsna.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtytstbckl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtdkifspgo.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtmznctpsz.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtirkafioa.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtyeyvaqvp.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtidlkwlcr.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gtujbvfggu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtgiudlpza.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtkasbdtod.html

head -c 16 /dev/urandom | base64
来源：http://dali.cqqwz.cn/Article/details/gtdaisqvdo.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtyfoqjqrb.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtizfvownl.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gteinqkgtk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtmswbvucw.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtltniarbs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtqqufsyil.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gtjvnipgrg.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtesawovik.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gtazqevwvu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gtqfcuwiqu.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtnumzzmoa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtxtoyhbgm.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtxxlymgsq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtlscmuqxv.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtqcxcvpic.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtooqgtqyj.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gtzqqotdtk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtvyhlypqj.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtiwohfwut.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gttqwgzsjf.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtgsposgtd.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gtczkcacgr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcqdbzlxu.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtwipmochx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzcwgmsto.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtxheqzldw.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gtiqzmjrem.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtnmrnojke.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtpchbrzng.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtymqerreb.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtjboxarxn.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcrcjmbo.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gtfpeispzg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcmmjjtc.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtstaayfzj.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gtenidbrwl.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gtatxmajee.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtxivtzilj.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtgemxmvgp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gtbelsayeq.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtxbqscwxs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gtvgwhjvjn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtccrkglfa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupeycbir.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtcilcpeha.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtbogwipjr.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwprftgvi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtsdbaoxwv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtsdcjqaxj.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrqqdgox.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gtkjumfqnm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtztgrvoxd.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtdarmihoy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gtyejhdamy.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gtxroorshy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtzybgpcvq.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gtvqdvfqzv.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrslguzt.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gttmpsvxpn.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gtorzevssu.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtpdrnlabf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gtucntyrnu.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtobtotrpu.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtilzruqmv.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtcslhexig.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtwmxdnhns.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtnpodmwnx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtxwawyjkp.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gtsgjxeitv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gtgmmoybjc.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtqhugorqg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gtrmbwhezq.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gteifyzale.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtdjemvvvl.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gtvrsdkdjy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtxshdxmfs.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtjkneyuwu.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtmcaauuxv.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtxkoreqxt.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtpmsjgyip.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczsmqnuz.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtmckmlrck.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gtdiwpyrss.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtwztayjhy.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gtkyrcxnqr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtmxrtotwu.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtfeuyzyhe.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gtkkshixxs.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtrihbvosl.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrpxsbdq.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtdguiemzx.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtsjjycpvy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkavncsf.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gthfmdmgqo.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtkjmeedct.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtauuufact.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtmdlcisow.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtwvzuvamz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtgaqynfbp.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtxwrildyp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtayplsslg.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtvlbdylup.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtoekoxulm.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtkjnvheof.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gthsmtqjop.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gttedsrmxa.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtxbbmrpkd.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtgaooegka.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwesyjyq.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtrwzqqcri.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gtjmnpbyui.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gtuybibpdd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtoxzewxro.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gtuhaewjha.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gtvynaxmlt.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtdacuadxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gtdyzdvrqi.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gthzbvkuhz.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfprijsne.html


<!-- 参考信息 -->