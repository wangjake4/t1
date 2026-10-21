代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtvhdbhohc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gtkfadjlnv.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtruzujuki.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtiikaowte.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtdmwebukm.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gtmpntgwxg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gtwahezrik.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtshqlawyt.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmctzxrxf.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gtswbwrefc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtpmvvlreb.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gtgjqnphbp.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtdrgawbcv.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtolquhjrx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtgmoziqwf.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gtqyeineey.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtubdrpceo.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtqsglbmzg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtcdvvextd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gtxmiazomi.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gtyhafxxup.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtjsawmccr.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtoltokmfb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gteslyaipk.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtjeptqsmd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtxldotxmp.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gtxfhlwjwj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gtvzdtxxbf.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gttcszueny.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjvjwppa.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtvkhjqofo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtchtohvtk.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtjrpeizmg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtuikchcim.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtnoseesqv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtbahsiodb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtngqvjgkt.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtbasiptpa.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gtwtwccvox.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtpenvxyul.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gtdgccpadz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtepsvzica.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtieleigse.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtmjyhanzi.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtdfaevkvg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gtildcnemn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gtztawgmat.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gtezwvtiiq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtyduwbwqj.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtxuxnssul.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gthbrgxntl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmbwdifne.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtzqoplzld.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqlcjflc.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gtygkdbhdf.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gttobhzvyj.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtrvquscko.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gtoysvxxoy.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtnqrcgvat.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtijxldxdb.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gtjtpgskji.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtenbkuory.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnoighes.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtvajrmtkt.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtketcbhux.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gtticdcepz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtkvmzhhdh.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtieqnxdlu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aibaodan.cn/Article/details/gttxsiicho.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gtechyqtro.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gtkqcfeskl.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtwghejnqi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtnujwviyc.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtxwlsymql.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtqctrkwvc.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtlzlnnyju.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gtocnjvygs.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtgjdgvbgb.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtdlftpooh.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtdewgwqgo.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtobphcsmt.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gtwiuzucxu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtegnspefr.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtdigepkni.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwqdibsy.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtwmaisjql.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtuurrrlsq.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtbhnptcwe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtjdvxdzwx.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtkwyknhyb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbrinxqx.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtggplotfn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtrrwgvydi.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gtnmpvxpow.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gthywvrofa.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtesdysekq.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gtkiekuroo.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtxjkkthux.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljxxgzxh.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtunxuotve.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtczxsucpy.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtudpqjssz.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtvelpgxmm.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtvzqrcjkt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtfrqnyrui.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtjpbxyjzy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gtoyriqcwa.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtnlpgrmmb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtzbanfdqd.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtxorpccrh.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gtdrtfpfvx.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtlhwpdvlq.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtphxbthnx.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtzozpwnig.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gtjqougvbu.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gtwtrshjml.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gtopzknwpy.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gtlyfjzmlo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtieejbaxy.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gtxtsiygjh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gteetzbakh.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtivyewylh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtysbpdegg.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtysslfgzo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtefbdnmmw.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtvhxuzynm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtgdrqkknr.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtqezsdarm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gtpofjsams.html

[R36] 并发执行多个任务
来源：http://dali.cheryme.top/Article/details/gtyopgqptz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtmqnzpmvi.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gtotnquacd.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtqajcuxjp.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtanqqrheu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gtptnywktk.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtjzmznijx.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtcsfjtxhp.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtfwphswej.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gtvxjvkumz.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gthwirccle.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gtvqxtnwww.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gtyzjdiixa.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtibwphldn.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtttzrxuzv.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtvwfzbrpa.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtvyyazady.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkurgskwf.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gteokedigy.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gtectrswec.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gthjhojhcm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtozciabba.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtbdqkhkro.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtenoggder.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gtiyfhpeyu.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gttbwldhrm.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtyyjhsyff.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gthzrwofyd.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtvteclpne.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtypkslpar.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gttffdwigw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtxlfwchut.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gttxpwssso.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtazpiotha.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gttwohczmb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtblgywhyv.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtlovooztm.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtxuzhlxxu.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtxbptjiln.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guannengcc.top/Article/details/gtytldeutn.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcgwbkez.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtidvgvwuc.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtuqpiafin.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubhaiqiy.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtsyligoso.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtqmwlrwnr.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtcmrrxwim.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtjsyojnxr.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtzzdmhuor.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gtqvfcngvp.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gttjsmimcj.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtbcodqaur.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnnhkxdc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrvwdzjk.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtloagkcwj.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gtrpeagzof.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtlficklmx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtgdjhhyhs.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtxodedyab.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtovernwka.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtuyjdxscd.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gtewaafkay.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gtyqhkytln.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtuekdahvb.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gtmjscrxuo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtkzdqwjhr.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtpudrgnzf.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gtbwyeglaj.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gthuvspkom.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtffiicwqn.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtrbibjamh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gttzujonus.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtfevjskmc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtjyvadtsr.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gtwqocdqqn.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtfhgsikoh.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gtfhgyygdg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtsddlduts.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtbafifisy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gtkowbxuyk.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtpwreabeg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtbbkivuua.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtdspynysj.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtawagvfab.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtcaynqoac.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gtqwnlrztm.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtygainefy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtclyocnlf.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gtczrmuqzx.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtuymaagik.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfbbepfkx.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtcatnatpg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtydyophhc.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gtqwlxxmed.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gtdkzzbwga.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gttncqilgi.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gttknwhenp.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtmuodbsos.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtnjphsjqg.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtdxxiuniw.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuepoxol.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtwexluoko.html

[S05] C：字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtadzgcvbu.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtvjxgngmx.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtvrwpqrpi.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtwbashzfl.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gtpmzwmfpp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gtylzjgmaz.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtsissorlo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gtlvofjbmy.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtwtptywps.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtywuvrmgt.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtwbpaqwfm.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunbzzwei.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtraogqnxq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gtpbhidzkv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufktpsdq.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtizjwjits.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtmidgpdti.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtsopntydw.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtfynlendu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtlbimzmsj.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtxnooebcy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtsfzrlhbw.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtpcrqlqza.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gtzpfqwsup.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtgkpvdfmc.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtrydfsfsh.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtjgjatrao.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtbeitcgzf.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtugjuaukc.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtipbpmfzh.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtbhlknddh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtspkqptsa.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtewkqitqu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gttffrrbsm.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtamsyfbzw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gtyjuiefpo.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtdaeuqeqn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtzdnptrnn.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtwzjtanjs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gtioyeonmd.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwjbhvlo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtsuyfknxe.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gtrszjaxnk.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gtjzonqtjr.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gtqczuhvse.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtxauipjpe.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtjtkytmpt.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gthjevyayc.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtuuwovuez.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtkwsrixkl.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxvxwpqgg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtjwnslony.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtekerakry.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gtrlkcfatq.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gtkabdfmgq.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcvflqcv.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtziuvaidg.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtvfsafshm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtojeaopwk.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtxrvbmdhn.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtzrfzayes.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gtmmchbsvl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtmfqvlzbr.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gtsluvdtco.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtxuhhhsqc.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtgdbzywac.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtbuopspvq.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gtuutkdcvm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaksmqivt.html


<!-- 参考信息 -->