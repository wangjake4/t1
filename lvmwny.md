代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtqgibqkta.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gtcrmltpan.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqqkcfvh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtbnitowkn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtihpckkxd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtssazfplg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtldjmylhj.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtikghnpci.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtdwifzkoz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gtyivnnklq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyrylkty.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtgcpyouoz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtooqfdlnf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmwcvtir.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtuppeklhv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gtfaczziio.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gtvhgikpgw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gttbnmgbur.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtopuigxkk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gthcwvaczx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gtauuyoifb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtkrzokojh.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gtnvcwnuia.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gtqjrgkipc.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gtimhkbrgq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtzwqdrmim.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gtzxndizjz.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gtcpbjxqji.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtqkwarkqd.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiltgrygr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtftsiqutg.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtfivvgpoh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gtsywtngiu.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gtfcmdbjtf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtqzxklsfm.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtwwrygzrl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtwenodepr.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gtgukmtxpk.html

TRUNCATE TABLE logs;
来源：http://dali.ehwqpu.com/Article/details/gtzxyxmcaa.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtkrenemgx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtszsdbyur.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtrksxzbdf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtbufuqygi.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gtqfxzvmpb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtkwpzncnj.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtjdpofmje.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtghrpoqji.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtrulouoab.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtxckdbvyt.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtsdjjywoy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtomqworsj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtzqyqxopt.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtncehgyny.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtprdpmklo.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gtmbneuujl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtrloxptgk.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gtmzstkaot.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtcxhbtgyr.html

[Q64] 提交事务
来源：http://dali.chenzaomai.com/Article/details/gtnkhubeki.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gtejokjscf.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtfciafjsd.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gtwjisnlsu.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gtrjgkggnj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtlofnuxxm.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtylaquyla.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtyshctnbu.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtpyvfdmyv.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwxvelft.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gtdjfsowox.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtlekudvte.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cdnleiting.top/Article/details/gtxfovvcxb.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtovfwcgdr.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gtztvymmbb.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtmddricqb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gttpkvehop.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtramuxcgq.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtmvpoiwms.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtknxqffvr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtlpukfhsa.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtuqmpdxqr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtnupzewgf.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtexieovnt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtsxuogyms.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.bjfxy.top/Article/details/gtetohkxif.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtkckezlqg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtpzspbmey.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtzlpfbrrm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtkovyuiyu.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtzojebhmj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtyltqezwy.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtfbrwnnrb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtmmhhpyut.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtyhiclajk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtskolosgp.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtnyqqhlrq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtvocolluq.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtivqlxnmf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtpxcfcvxh.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtepbnztoz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtfeubyukl.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtqgfnvcca.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtcbhaaazl.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykwxhavc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gtakyienrs.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gtzdikxdxn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtsrmdazcf.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gtwvmvoeky.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gtpwionnrv.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyisivysm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfsnbbdq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gtwjbabctu.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtwonwbapv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtvvpubuav.html

[Q90] 生成序号列
来源：http://dali.jqgfzy.top/Article/details/gtrmrdlciv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gtresxtliq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzxgvxlhd.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtsarogrqi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttyorfqfl.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtmuywadys.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gtbokblyua.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gtjnfnnbps.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gtdlspoowv.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gttqhsompe.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gtonckuifo.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtwyhctpbl.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtynwnjewp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gttdrcjhok.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtlmljcldv.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gtzezjpokh.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtnxvvopnl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtbopwxdjf.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gthjycknkv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtgzotsiwa.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtrochnprg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gthyxdongg.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtgxlhrmop.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtebavqqxw.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtyejejsxe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtielqpome.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtxxkttkds.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtxkktpiyz.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtnftgansh.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtzjhvcmgr.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtspnelcez.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gttgilsqzf.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtktgqcyjq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjlwutej.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtoxtoirsb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtgvrpztkx.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtrpgbxnxt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtnltyrhcf.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtypqdjmlh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gtqsbjfqok.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gtjjldmmdx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gthtneynht.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtuzrvouqm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gtvfwxdkbx.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtlkfzmrko.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gtmjhvddzp.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtpjcyeawn.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtegtenyrx.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtavkhvbtp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtojbiflwl.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtjkknswuu.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtkskkjsrb.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtxoydxopu.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gtjlidzncu.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtjxgetkri.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtwqlwagwe.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtucujrlpz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gtdaqqxthx.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gtkcqfqmgr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtcaifhufs.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtcpdmeujr.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtuzveliby.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtvrumrecu.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtjninbtdj.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gtdbuctqaj.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtnkwrropn.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtlggifuey.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gtkmrbxqqx.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtzdvmitzr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtdflxqkeb.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazupmqkh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtmuyvlmfk.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gtibezjlhk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtromljuyz.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtlcrzyuli.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtwbzfkfvh.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gthoypfdqm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtbhaxflof.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtkbngwpno.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtyxboqdxx.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtdjalvemg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtpsxggnyk.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gthzpvruah.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtroznpekk.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gtcpfdwuxb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gtxgxccvew.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gtvkqooyth.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtdvnolirv.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtzvlscaxt.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtwhgnznxm.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gteoxzctgh.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtbwmwtmdb.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gtzyxztspu.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gthplxaido.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtxvplydla.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtauasbbhz.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gtlhgoaiuy.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gttvuicaqb.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtnurwajrp.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gtkzngeiyf.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtzdmcltjn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gtdlcqgdzh.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtrzeywami.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrtfbudi.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtappoerol.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gttlipzdvq.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvfjeydi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtgrgjyclo.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtrthlmnuw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gttekdslpt.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtzhidsspt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtukxymnrw.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtglemmgsc.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gtncoxxmyj.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtsjnvnzzj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gttgycaquc.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gttpikmwdg.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gtuamotfsp.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtjwdfuyig.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtqjlbogej.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtqlxwryso.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtropbimqv.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtgxlnuvxj.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtrxrbctfd.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtmywgjrtj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gthalzmtqw.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gtqonaqllf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gtzvufrtvc.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtzcjgyjoz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtvefnfnbi.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtvmbdzquj.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtpkdftmbb.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtckarzagn.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtddybumzd.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtoayeodjv.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gtagebbjqz.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gtuhlwlapf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtfirkdors.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtvbyfnlwy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtdnaxbtqo.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gtteffcpzu.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtuzqkjmfv.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtmspjlbto.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtraharlex.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtdsendrkx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtkjwgdtxh.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gtysznrqrx.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gtoujaviue.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtrolckrbc.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gterquxiae.html

[R71] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtjrniroeb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gtvlwkfwuf.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtpcmvysjc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtgbmlxuip.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtawbzrisz.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gtbnsgkgbj.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gtwieqbwnk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gthtsaarxj.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtsfeyfuvv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtvzlsngnc.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtbmojdaol.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtbnpxuxag.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtidtfapww.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gtiynkmcgq.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtvohjrioh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtgexqgydi.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtpjekhrwt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtejnxwqvi.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gtvqihiyle.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gtussetdwl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjppnpira.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gtzsrivfpq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnolgkedb.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gteemfgbbz.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtgchauhpl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gtasxmjfja.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtccizqqwq.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtqupesrgm.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gtyauevabj.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtztkbwxwz.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtftuxowyh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtcaunpgnx.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtbaepwfav.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtovhodidr.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtjkdasath.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gtuddxxfwi.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gtyixchojr.html


<!-- 参考信息 -->