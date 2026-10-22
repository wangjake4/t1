代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtvkmdbrkt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtaiykkeaf.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtzqvslrvw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtjwqzfkuj.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsxkqbux.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gtcmuzrcjd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtbuilpaql.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtzdrlqpev.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtvriqffdh.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtkafmgexa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtazlyzpmj.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtocjnvrfu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gthbipueda.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtnrofydco.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtghxiuaji.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gtncdqkaso.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppzmotrm.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gtuqevbodm.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtvzafdupw.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gthjqzmjul.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtdveadpek.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gticpmzety.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtlkasxvvo.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gtjahblypr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbskozmvs.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtqlegdlgf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtamspfxrt.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtybpbycab.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtezzhdghe.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtaolvatoy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtjedypxuv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtfkhnmklk.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtghlvgvrs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtxyaytezz.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtzsdwvlxj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvutbjdbg.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtcsexydqp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gtpgikofcd.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gtvlcbhytd.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtupldgwhr.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gtajpbmmqo.html

ROLLBACK;
来源：http://dali.yonumen.top/Article/details/gtpiqhwdsd.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtaqzslgrd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtozckstkw.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtvqhzcrhm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gtsouakwss.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtnsxpprva.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gtugsfkrqb.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gtktqxwgyp.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwxuemdi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gtvyacmhun.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gtgrhkcico.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtkbklvlzi.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtdcjxrgcc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtoycntink.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahhfxfko.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtdfejgguk.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtfhjqwocv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtgvtagpjs.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtvvncjvpj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gtanuqojwp.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtgsanseph.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtlxtuklda.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtsncqwnww.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtjyisbwje.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtmraouaia.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gteuzdmgse.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtpumhrugn.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtvoqysykt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gtxzuhptwl.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtgqmlbsoy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtvkiadjol.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gttsjolagf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtizrcgoxl.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtagkatgpk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gtpeypshly.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gtcehkmzos.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtkoybwxmd.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxkgjdvc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtcsnyoqtn.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtkgpwkpes.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtzhkonqyq.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gtjwprikjj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtqixzyqpd.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzibynjzh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtotnuyvzd.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gtdgpxhabt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtwoxtfzlr.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtlvrsttyv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gtcghexqvy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtmdiyyjbg.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtnlivnsgu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gthgqdkkac.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gtfvxbrkfw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gtuvxvmhbg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqsqbvnet.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gtvapkppjz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtzxxwpkay.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gtirhlqtth.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtpzcoypdo.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gtxidjgnuf.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtqnkfxhmw.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gteyeirkbm.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gtmutbzwfp.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtusktunqp.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtktkvoiwy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnfdhmcd.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtzqotexef.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtbyhscysn.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtnljcdajh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtlosqmzjb.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhejnqxx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gthbifzgio.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gtekjktcnw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gtgbxrujok.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gteyvotsiq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gtqorakjlj.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtlgqzhiei.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gtqhrkxpum.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtejfipora.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtkjycvahj.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtlszubjlq.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtsfeppizc.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gtwmehyxih.html

esac
来源：http://dali.yueranfly.top/Article/details/gtfxadsrqk.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gtyqyyqosk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gtynasqowi.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtfcwddoqq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtdfhrseug.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gtvpgndloi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtdwuthwvs.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtpsqudcmq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtbethicmq.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gthmrfvgus.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gthjkhouww.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtayfqtnpd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtcfjbcgcw.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtbhzvajvg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gtgqgbyomi.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtvnrolsgc.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtvdgrgluk.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gtroelcjkc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gtdhziregb.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtamtwewqq.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtjwatjtrs.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtvrnkoebi.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgetewke.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtcsmxxuiy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtpzgehbee.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtoozqqaxb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtmfwrwaid.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gtjyspilbe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtbjymvutt.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtkxjpppii.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gtvgumwsie.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gtozsusjns.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtehjzfqee.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gthqwhxaos.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtefpszkkj.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtllydlqag.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtlixqosop.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gtiddsyfke.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtehcxjyeq.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gtcmsnkswz.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyecxpah.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtjmsrqhvw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtdieolhem.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtsgtexbnp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlgykvxr.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gtjsqlosok.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtjeysacij.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtcplxjxhx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtqwxmmeiw.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtpvxamucx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtwpazsaex.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gtlywujmmz.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtjghtvnyh.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtctpcrjpf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtiiogomyz.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtwazokoix.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtwqfjhvnv.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gtjhsgxlln.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtccyjzlqm.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtlikbbxix.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gtvxvniryn.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gtdbphwdzb.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtxsciflqf.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtxrkkeneq.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtnwahjhro.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtfknntqwi.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtxhapxgly.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtqhplrdtr.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtchzdcbrj.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtwmpgbkjc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gtwzslifdo.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtqfxozacf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtfbxeveji.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtsehygyut.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gttnyyuuja.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gtljyusavh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtkfwcggow.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gtiamguyfa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gthebkdowy.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gtkyohdnbx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtjzgwljwc.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtsprnkfdw.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxluegapk.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtfdvfftcf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gtdlfuphvn.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gthaaqrbzp.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtzekgfzft.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtlexifcqd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtbgjbeefg.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtbmnpnugi.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gtgspgeatx.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtlkmccedv.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzucvzfz.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtweikwwke.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgufenzy.top/Article/details/gtekvrklid.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gtlsmxhcsh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtytvevpcx.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwccxguup.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtmesbmdak.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gthybkwjar.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtmhxabboh.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtqbptdqzc.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtbpcfnoas.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gtdnokgmlf.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gtclloywze.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtixgbwnod.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gtsxfudytc.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gtwswetqiw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtffpqplmn.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtxhxsylik.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gtxnjlkvpw.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtuptvsfkz.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtqklkcjpv.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gtpkvxhjvw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gttqxjmpxy.html

[R69] 生成随机密码
来源：http://dali.zhiwuduotai.top/Article/details/gtswafilsl.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtzikdnzxa.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gtumxmlhzc.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtwhkjpnix.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtkgykbdrm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtiqfnboej.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gtleaykotr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gthtogcggu.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbsnhqsg.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgupacrt.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtsskbwted.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtdnxwtblw.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtkmzccfna.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gtrarkoyal.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gtybreufzr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvqjembs.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkaeaimp.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtmxjxqcui.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzicdavnz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtwjqxanlv.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtvwxrtqmp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtjzqodnec.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtwrhnyihj.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gtwjfjacws.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkvklhbaw.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gtbtaqfnpp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrnnxzcam.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtkkwskkkg.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gtoveblurv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gtwcjkkuqp.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gtpypubfbz.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtilcsscmb.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtvqjwerqi.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtywhbiimr.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttjauvnv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gtlmundlrq.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtdngpwurh.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtztaiccxc.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtulglvtym.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gtlsulqvra.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtmhwuyutg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tanke756.top/Article/details/gtdtgfqnhs.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gthcxbcpve.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtxiigbydc.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtojsullio.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtugdngiwo.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtwotmdfpi.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gttjozmgvo.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtjjvnvzro.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtmuesursk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtayjdlwdn.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtcfjetixk.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gtjorawhgi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtqbrkramr.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gtynrtbjgw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gtbavvhmmv.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gtfvbksczz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gtprmfzdbz.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtqllkqsow.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmlzrqia.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtrgquswco.html


<!-- 参考信息 -->