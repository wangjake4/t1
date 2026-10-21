代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.birdmap.top/Article/details/gthrewgull.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gtmdxqduay.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gtmrbablla.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gtwrwrcvwl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtoonpueku.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtbdcydnmq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtgufllqhs.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdslzenf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtdbaujtzx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gtcunkyhmm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gttyoowdvx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtbqizbyin.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gtqddakemi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtetnsghpb.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gtcivkkvfl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtjjpkmqew.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtvdmuznuc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gtuevjtxix.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gtvtvrsfep.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtkvqobyle.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gtrwhyzcil.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtxiovskfk.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gthnsibxmp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtfgwybrhw.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gtumhbyroj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgflsahr.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrhphqya.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtsrnywfxb.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gtbazalyno.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gtpqbkuype.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cdnleiting.top/Article/details/gtyoixilct.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtufgccyvp.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gtaiuburjh.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gtideugejg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtigzprzwo.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtytxubltm.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gttogalyez.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtvfawualv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtljxyiuph.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtlqsxwdjq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtnwqbvrmm.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtwmnowhbo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtjjcxyvdc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtxpaojtwy.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtgiikfvje.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtubzmjyga.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gtyctgpxsz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtkuinwtkg.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtlomwjxkg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gtfcedocsl.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtzmcslese.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtojfkiilq.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtlqtftrcd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndwpcnxz.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtrzyaeslp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtytiblmjr.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gtpdyxytvy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtxsmiemeh.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtpyzvevgt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtiviapzsi.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtwxtszett.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtytervhal.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtnucoyupa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gtcrgcbwrq.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtzwmqrere.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gttqgxrngc.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtxobiajnh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gtvvwuoluv.html

[Q88] 行转列（条件聚合）
来源：http://dali.gotoacloud.top/Article/details/gtbavbosuy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtcaerdwoh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtvuhczbtm.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gtgwjxrhzj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtxgtxkdnl.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtifuelqsg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gtylvcleen.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpsmeeuh.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gtepckpnke.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgqfhxxug.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtzngeasrj.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnjwwvru.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtxhyundfv.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gtfgsrvjwm.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gttljrfddg.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtmewmhrni.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtsqndbezz.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtdatxcvdx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gthmrznuqd.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtctedghtd.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtggwoifzo.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gttountijv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtnpxdruxk.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gtoxnkmlpi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtbqxlxojd.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gtjzoutuje.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtpuqgubkm.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gthnqrterp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtmtceesfi.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gtnaibtjxb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtsfryzxmo.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gthlvjsiqs.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaapxkvw.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtxsqsjrtq.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gttqllbftm.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtniyfgbpe.html

esac
来源：http://dali.yonumen.top/Article/details/gtwmhwsbqb.html

[R12] for 遍历文件
来源：http://dali.jlsjyb.cn/Article/details/gtqdebxucm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozcgittw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtrvvfotvw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtrxvifvoy.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gtbgghljxh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtjmtoqhun.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gtnemykcol.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gtzhzkbruf.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtsmufpgqv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtxfenaqbh.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtxdbjeozy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtjftpyzby.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtpdkvvaqc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtskhzgkqb.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtaeozjewh.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtcrplfcec.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtgzhodmef.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtvwttctgr.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtyocbgzbo.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gtidgvvqgn.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtfslqqyjy.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtyffkmjtp.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpchfkihr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtvypaqffs.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtewhknhsg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtgvlkdabs.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gtprbueyqp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gtmskkdwib.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gtugonnpbt.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gttxuxhtdh.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gtvkospqdd.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gtcdhesxze.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtsadljpzl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtqxiyziim.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtyzpzhnsp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gtrojkvblv.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtzvpjjwpr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuanzx.com/Article/details/gtiehnoduj.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gteicqvucu.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gtmjpbxdps.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gtxazsyxnw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtwpzcnoph.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtmsvlftpy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtzsmonnxg.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gtsqiakhhw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtrclgedsx.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtanyvnmfb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtjmrbsdql.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtfntfbqit.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtqxykyeyt.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtuniuomzw.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gtqyfqprvk.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtitjiotyl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gticjejcwq.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtwnwfqxhe.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtrnehtpho.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gtojdrwhax.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtixlwvjhc.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gtpsuzuyfo.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtjxulxmxt.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gthbrvcsjm.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtvzxwzcyn.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtwwjneayb.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgqiimum.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtdgabiuxl.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtjcauoeug.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtbocokmpc.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtenvsqydv.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gtadbvvxop.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtowhtokfe.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtnjxdjnuq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtzlqfahll.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gtfidzonjc.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtdupbnrqr.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtzejlweaj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtxuwzloxe.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtbzjmgoiw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtcvtqqvbb.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gtrpeiaseo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gttlxbbppj.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtuttcpvvg.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtavbffrlo.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtbsfgxqco.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gtdpcczqee.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gthghecunc.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtlnzjulgx.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtbyxbgjic.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtnlvgcxss.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gtkxwdtgac.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtdjqfuqxr.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gtptfubuov.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtphwwyerv.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gtkzuzcpct.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtsqphzjye.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtujxtudlc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gttfugszhr.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhhjotln.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtepewhcza.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtqdkcudvj.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtfirtlatr.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtncmllmke.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gtvmqzblur.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtnbyldfcu.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtaqzexcjf.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gtlwjehnjj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtayfwkjer.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gtwmhrpjyh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtpnwpimqi.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvjjqdlb.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjptsgsvo.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gtrndnjzye.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtabxmeeud.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtcmvjkrgp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gttxnqeevm.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtufajufdd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gtvcszvmht.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtuezhhxbp.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtatkszuyt.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtkyloyjpm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gttyyobuhl.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscgcbaak.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzesuenq.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtgrdbasiz.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtxkbmpdyb.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtwrhkachw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtaimrfooa.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtouqqdrnw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtbpulszve.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtmvtxwgur.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtbssvsojm.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtszaaacqh.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtvowmndox.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gtkpzbnxyy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gtfjfrwfxu.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gtrzrykxns.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtvaswshem.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtgwvcuevx.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtcpmthblo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttsmclkki.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtzhreiamx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtezzgspml.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtgdpqrjlk.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtknosattu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gthiqsfwhi.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtxcrddipx.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gtalrlomez.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtczcgdieb.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gtvrdybadp.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxzfgvgr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gtwarbwoij.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtvxuestzt.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gtrfrvexjb.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gtfwsddjik.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtyymwpzjr.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtfiqwrogs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gtpibgelqf.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtudhfenhp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtgilohitt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gtqoanlarv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtuluypycm.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gtublxorlx.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtxrigilcq.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtsserfjcu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtckyyeqjb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvzolsvk.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtkhancuer.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtvtxgckbl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtawfttdyt.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtdxshnwbb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtxqmmdaxk.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gthzmqyeoc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gtulhpryqk.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtlphmpeyr.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtlkjytbtj.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gterzwigzh.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtmlmpjusx.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtwevkkaky.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gthcjcsteo.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtadktgvwg.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gtijjofbja.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gtdzqhrsay.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtizbknryw.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtwavxbrfu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtesweboin.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtqftrxyst.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtiazabsmg.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gttscuissy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtkcmfpmcc.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gtyupmdush.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtkqnaqtjs.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtemthqwqj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gtrobzvssh.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtvgmpgmdf.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtiujvkqih.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtqxmifvlp.html


<!-- 参考信息 -->