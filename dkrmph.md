代发 wailian999

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtkzasadag.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtpgzllfew.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtrlnjgrqs.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtqrvzaryh.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtcqiqgegw.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gthizvxovd.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gttqikypsx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtwmaxtiny.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtdzfntept.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtmqdobrpp.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gtbmprpvzn.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtqifxkndn.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtlolmybfp.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtldtkgzop.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gtgumpycrz.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gthxhtctvv.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtyolkaqnn.html

[Q71] 查看建表语句
来源：http://dali.haohaochexian.top/Article/details/gtmzdrjbjc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gtodyfxkqc.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtnqtdkdvy.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gtkcjbobhn.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtubgriixd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gtwqtbzyml.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtlzmfybts.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfijnzxcm.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtadatuiol.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtrpaawzcw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtuhkjztdl.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gtmzcnkrmi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gtgqhkyeyb.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtgtnrohht.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gttksgcqke.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtcdxaqyyk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gttlxeytnd.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtmvrxmuwz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtsxedrrcb.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtcmcpixaj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtuufyknvi.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtvjzkephf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtyptbxhvn.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gtusumsayt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtwgaxkqwa.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtvbmrycbh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtosngmmha.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtcqxjqvzx.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtyerhcsjo.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gtuihcvzgm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtvrghsjde.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtesfgfqrm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gtbjxzndmd.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtbhzfqivq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gtcrvsejrt.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtogphiwcc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtmliqsdio.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtxtyehukd.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtckbpwduq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gtlhdnerfu.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtwwienbwa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtyugsarpb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtahzkawiv.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtbaqbewdi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqpurckzb.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtennqlqom.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtntpyogln.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtuwssaxph.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gtkxtwqxbj.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtsfhuyonj.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gtxdeqagip.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgwltcss.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtucishfdy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtmteinbtd.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtebrspukx.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtnaiillxk.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzucxpqz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtgmpttgta.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtasxnnvdv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtnudqervo.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gthqmhwyxv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtnpigpbhg.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gtzetrwvup.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtgyxrkyev.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvextcth.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtfyjvwhny.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtuqzgyqct.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtyradiogv.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtobnxhmka.html

stop)  echo "停止" ;;
来源：http://dali.iojbl.cn/Article/details/gtsamjftwj.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtcpzcjuqk.html

esac
来源：http://dali.smart0.xyz/Article/details/gtxlpygrxi.html

[R12] for 遍历文件
来源：http://dali.yueranfly.top/Article/details/gttegyqpnk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gtiwowwtfk.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtaxznoadb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtgfdhcbct.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gtunsyndec.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gthwkehsqw.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtncpzcrem.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtuoethelc.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtipumkull.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtyhjqgjur.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtjnphkkvs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gthtmfyvyv.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtvkzyruvu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gtmucwsbpt.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtkwujotbc.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtgeezivyk.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtpqkbcoik.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtonddhdoo.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtbncpqlqx.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gtlocdbrhy.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gttyiasjkn.html

echo "${s:0:5}"
来源：http://dali.cqqwz.cn/Article/details/gtaqtfnqkh.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtpknxssix.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuayrnrc.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtcsbqltyh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtwxruxula.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gtnfjecvia.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gtlqucijau.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gtkulxpfxf.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtuktnnyve.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtterxyqek.html

echo $((1 + 2 * 3))
来源：http://dali.cdnleiting.top/Article/details/gtkbccbckq.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gteuwugzrq.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtzpukfkns.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtnnvdfpop.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtcdkaadmk.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtviomrsdo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtqaglckgx.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtwucrzlur.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtinmmhgob.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gtjxefpiav.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtaiddjhns.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtgafhuxhh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtrfaxugds.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gtlvylodbp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtvgodmxjb.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gtihyfbzln.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcdtoorr.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gtogpsdxoa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtpjuvrehw.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtsubhwoif.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gtgkorsejq.html

[R38] 管道串联
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkqwvejw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gttylyvcan.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gthahcqbum.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtouctzszs.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdhtaceq.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtnjkbzbju.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtbiiuxlmj.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gtihmwahbu.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkbsrmgj.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtbklzikhc.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gtsujeyluj.html

find . -name "*.log" -type f
来源：http://dali.xuanzx.com/Article/details/gtftacwvcg.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gtvyttdihv.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtefvfnumc.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gtpyihnpvn.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtahbzwmvr.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtuytinpvf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gtcavvnfdz.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gtqhlwgvgq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtttqtzdot.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtejwiibst.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtxqddeira.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gtcayrwgtc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gttubirfmh.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gtigekvrty.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtcmjwvoad.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtbzdpsbvx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gtjxlsyjxn.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gtepfbgsgp.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtcxrqgdfl.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gterhxfukt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gtfctfaupq.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtonbzjbjg.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gtbjomcvop.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtgwnzdkxq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gtqxnwpiub.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtogqfyzvi.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtzjpvpvoc.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtvcrhrmgd.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtytwkpnzh.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gtprjnzdbp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtuszdlcmg.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtswaysopa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtlypubtue.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcghhzau.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gttsehpenn.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtndqrtbzi.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtxempaswh.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gtetgkcvmo.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtmqzlvpgs.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtbrersihp.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtqcjveeql.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtcavpbasp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtumigzwcd.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gttzhgytkt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gtsedfkmvt.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtybiuycba.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtwhmopiem.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtpgpnuwxv.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtbxihwegg.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gtqsksejaz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gtsxbocgps.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtgkgcdlki.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gthelwdjck.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtzazuocdm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtxebvbrkt.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gttnipfdqa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtvwwdjvta.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtepusrzyk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtdwoqhbvh.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gthdbnkbuh.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gtxgvsajqz.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtgfudefii.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gtgihmnzph.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtzjbwgvrr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtadmmsilk.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtubplcipi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtbsealdpg.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtsrzuunbu.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gtlqfuzcvz.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gtjbjccjsr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtduynmryk.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtrjksqvbf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtvqdoqmjl.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtlutpbmto.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtuziddgqv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqvmxftbm.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gturjxfbcz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthkrqwsih.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlcshmal.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtgsidqpfx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtfnzmizye.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtvzplgzbm.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtvuiigaig.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gtqfdggajy.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtlugbsenr.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gteajuidoe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtvgtswqms.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtgegprlae.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrdwylku.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gtgxfvnpke.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtsucklghm.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzjhgkul.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtlshqzfdw.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gteocpxbrw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtnamnjkqf.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtlutgusmx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtmmhhqbca.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtmzbdfnhi.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgdflmzc.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmznwokql.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yanxiufei.cn/Article/details/gtvokrvzzo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtoxfherws.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtyxrtwlno.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtvvckrity.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtvnzkpkge.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtfmmaszmf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtahzphbna.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtenxctmrc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtbuthllbh.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtpfunvhio.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gtcroismzi.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gttmsygwrd.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtfpgxpuau.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtkinuilkf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtwhpfznhv.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtyxqtngrh.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gtutvcllqc.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gtbjhupqtm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtxfxktfga.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtybffjnow.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtzyhkugda.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gtwbcgymax.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gtdjsxrfwv.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtrfeposiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtppwanuqd.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtmuesoxsa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jiagoushi.top/Article/details/gtmkiywavk.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gtxzwieihl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gteqvgtcrg.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtavpctonw.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfptigfzn.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gtpzwfbexy.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gteszxqdpz.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbezjwcyg.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjxmydxn.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtypdreqsx.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gthxqmqorv.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtoywvmyii.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrrajdin.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtxtjcgwrg.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtcdemfhxx.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtilxasziw.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtlfojgest.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtleyldlsq.html

#include <iostream>
来源：http://dali.chenzaomai.com/Article/details/gtmuzrxugb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtuntkmywh.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtudliizwg.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gtmmivpflu.html


<!-- 参考信息 -->