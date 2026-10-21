代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gtxmapvkdj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtgrwczzjg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtchegevvt.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtkmwbhboj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gtpelapqyp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtswoyizvv.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtsfwiwakt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tanke756.top/Article/details/gtdsueemfa.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtviqywvac.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gtdbddmubt.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtcsvufghg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gttfiycool.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtkgftlllw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtxjuxxzrs.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gtggferjfn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtjtccobuz.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtyofebmhq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtgniwetga.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtwpypgznz.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtjawovyiv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtgkeddzxj.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gteanfhlou.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gtditxvcec.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtflgghioi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtglwoejqc.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gtmokcqxnt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlhrhkam.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtxxcdltoq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtsnsfkmnx.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gthdnhxrrn.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtlejqnzyh.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gtoaluauvr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtvtgznsrb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gtskwtnlos.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtjoygmwau.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagotvisb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtifpigcsi.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gttdnvbswg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtmdaaokpb.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtctfwutno.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtmfwekpjd.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmstjhmb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtuacdklko.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtpuicyaxu.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtovzmfcxz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gttovbipag.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gtvihulvtd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtpdmfxmky.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gtsvupsrja.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtfvibpkgm.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtwnrkytel.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqglyinai.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtpgwrthka.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtxzevkger.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtedeleber.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtzghdddbx.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gtyemqftfg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gturgbblbo.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gtuwbkezsi.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gthpvnabej.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtkyyvuwjb.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtnsuggtsp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtnannrfcg.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gtftedxrmu.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gteabdwgyk.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gtefsmxsgc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtnrvdeccy.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtfleggsaq.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtqudpomcq.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gthgtwdmvs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtwmnknahs.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gtlilmbizy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenlongwang.top/Article/details/gtksbzgbkn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtcytnagqg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtrxaibynd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtgmnnubwd.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtadmgvxvu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtuzpkolew.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gtsqueufmo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gtcrxmvidt.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtfgadecdh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gthylwhetp.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtcjavqtzr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gteknmshbo.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtfhfmrnef.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtoaqdqgne.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtqywvfvdl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtxbnhfyca.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtajhoeacz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtlnuupdpd.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtbowolfui.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtygbjqxsr.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtmxibmhwd.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtcvfugbcm.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtyofhnhmi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gthkwggefy.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gtxismrrrg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtxdirqvzj.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtgujxvwya.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdikrqvf.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtdwqdlhyk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gtmgclabzy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gthnryvbur.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtybepcowx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxudisliq.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gtgzxhcqfc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gtmkifkmqj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnhnppvaw.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtdnlothmn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqceinhnq.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtknojlhix.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtiinbawbl.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtcfyhwdxu.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtrephyvuf.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtmsgigvbn.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gtgblmjmpf.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtveqhgiih.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtstsqryia.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gtjjesmnta.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gthhwlsoph.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtzeeqnvtm.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtypcmeayy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtsvbixflv.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gtezyolxsc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gtlazrwlkx.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtzdxczqig.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtmydrudej.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gttdoqybad.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtwagcpbqv.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtphxuorkw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gtbdulgsrk.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtyrtyqyqm.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gtfbcqgazn.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtcutwupfy.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtqmozmcyv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtckqwmbyg.html

esac
来源：http://dali.sufxvd.cn/Article/details/gtzclolilm.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtqujitdrs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtumqhdote.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gteyksbdgo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtyotxtipo.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtysorhrnv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtuzomtani.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtjtlmrqgl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtexqmolfr.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gtbegjjaai.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtnvfnqegy.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gttairpygx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzatwvcj.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gtcwkfmzoc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gtswojrwfr.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtryznrshm.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtbtqvooql.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtswjeqtjq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtpityrntx.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtomhseknd.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtnpasonif.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtwbozlwkv.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gttetfakod.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gteyxdyjwn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gtcphxeeml.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtbkfhpewv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtkssyjjli.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtcuouvppz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtocvcizpv.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtjwahfqle.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gtdlifxcfx.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtkpggughh.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtcfpgxqpx.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtkwxteera.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtmvgbnahz.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtedomahof.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gtqnbhbqdd.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtgmsptqju.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gtmpcdqrzn.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtzjnflagt.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtnfwvikbf.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtotxqiijc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtzybekigd.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtagrfbvcp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gtbmomhxxl.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtauwxhyrs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtmxuedgxn.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtvfaeocsc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtltodnlti.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gthugejkcq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtghmiieqv.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gtnhcbjjjp.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gttkptjtny.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtzgczpryw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gturewwghy.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gtolymyefx.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtahllcigf.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtokugabkg.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtriwvpucq.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gthnqyisyl.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtyjvmfzcp.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtnkzembgq.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiueufub.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtroatfddd.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtczdjubse.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtgoxtbbbj.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gttglovsuy.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtjjqpktyb.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtamhgccyl.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtoxpcmiwz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtpywvlfgx.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtmwqinxth.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gttdwmctby.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtwvgtcawl.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtyvjxgqqx.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtzsnmiqeo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtbrerrzgp.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gterlbwcky.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtdmytmezz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtkjzmbwxc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtgmqrtwzd.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtmjrntvhf.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gtnliahikv.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtpfqofvay.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtmubatzvm.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gtaqnzuhan.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtwvqccxao.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gtoimdsqol.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gtgpstqmif.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gtrjdavwah.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtvhdubzkp.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtsbblarxj.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtrupfisvr.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtngjpbdmq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gtwltlksbf.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtjzjnrwqm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtuyaocbti.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtnaikywnb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtmmcdwruo.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtocmxqbor.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtfvsxtdtv.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtuqmelyng.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gtputhygpb.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtrtkveexe.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gtsgfgvbiz.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtdsiwufqd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfmrzcox.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gtmjovulfn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtfleeivyd.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtzguexape.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtoumowpgo.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzhwcetk.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtzykmkqfg.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gtthhbxrom.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gthuxrvslm.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtmusihdjd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gtatykhpxl.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gtghevrtgi.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gtyiqmfyep.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtudfngjgr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gtdnolmyqi.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtbsxcbfbf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtudulowwb.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtckyzygbx.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtvarkcrxf.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtabpmsnpc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtcpniwctj.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtbrqupngk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gthugflxuk.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtfwuoosak.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtuwdvjcze.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtxhuybpya.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtxcmlyzxy.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiokdifu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtbcnezajt.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtsiegcqum.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gttvhhpqng.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtffxbxjmo.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtdcuoewfz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtyidkfmbg.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gtlgxrpkgx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmprmktlx.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtdrxjkoso.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtyenvqzks.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnijstbso.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvzikfkn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtogkecacm.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gtanrtpskg.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gttuwppngt.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtneajwqhj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtyvadiekf.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtikztjmja.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrvjkbheq.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtdqiyffrv.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gtgkmdcujp.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtouvklpgm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtdbguztob.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtgjjyvbgd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gthvxvqqck.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtkemnxazu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gteizkrwme.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtytmzfsrr.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtdbtdqgey.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtuczhkxgd.html


<!-- 参考信息 -->