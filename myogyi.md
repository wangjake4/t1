代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbxztrcd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gt2uhtawuiu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gt2vfvfoeij.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gt2tdpnhpjg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gt2atwvmahn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gt2ronjuxlg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gt2fvmaukug.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqthpaqg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gt2zutoedgw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gt2rmsbzunt.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gt2qmmzhylm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gt2kpmraiwh.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gt2wvkypemh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gt2ymlqidhc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gt2hpwhxmqe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2gbqaqpam.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gt2pbyvmnjy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gt2oqcxefac.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2xfetzhil.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gt2jqzhiaog.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gt2ybqjszgx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmdyzdbv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gt2glmmitxv.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gt2fslplxyp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gt2qjwvsfri.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gt2xmvebpma.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gt2fdjqpqvc.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gt2wzppepuw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gt2eqhswkfr.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmdlnqqm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2mfmooajc.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gt2avfaxuqv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.birdmap.top/Article/details/gt2ohhuscyl.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gt2dipdidfk.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2envqdwzz.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gt2zhpjeblc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2fqmofxfi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gt2fartzczj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gt2zmbamhlh.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2kgpcvcyf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2cpytbazl.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gt2izchxewv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2phzxpsld.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gt2oucnhtsm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2apbvmgef.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gt2enuxgtaw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofavggeb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2jniuszbk.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2pvpuyiqu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2bsygtqqv.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gt2oumrccjg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2rsupiekv.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gt2kcfepijo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvzamjcn.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gt2spmgbngm.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gt2tpomzltp.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gt2pyeexwrn.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gt2qafzfsrs.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gt2nxbcnpwo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzdxrjkc.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gt2abfkmuya.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gt2jgwlhcbp.html

[Q68] 保存点
来源：http://dali.gotoacloud.top/Article/details/gt2mjsqdjks.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2jjzqmrxz.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gt2uzcpdldp.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gt2upgkszey.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2egrgbkit.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtltjftq.html

ANALYZE TABLE users;
来源：http://dali.nwbrower.top/Article/details/gt2fvcneeja.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gt2cydatnlp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gt2zbzjsmkb.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gt2pkvjxovb.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2fkrbmrqm.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gt2aegzsznx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2hrxxifuf.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gt2skdpvlzw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gt2htgakhcr.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2mvfjdtyh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2bdjnnmuo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gt2fsnnsaec.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gt2hmufkwps.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbozsjn.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2fmnvgsgq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gt2hnvqdybv.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gt2maseuxxq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gt2ldumhczj.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnbjdmef.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gt2flkdanel.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gt2qsrminqh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2lhxfoxxw.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2ggehdhpy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2guupbkko.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2ioizrhzy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2qxjqyhof.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2qfyddmsa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2lspjlbtn.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gt2aajthvnr.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2wjtybeqz.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2ojjqrhxv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gt2cdpuwedr.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gt2mrklsflh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gt2zccbcgmx.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gt2rlshibty.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gt2ofrtrtci.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gt2vscrkdvb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egbfrhdp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2htjhqmyx.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gt2azwofdmi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gt2uqlevqyn.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gt2bjvfznsl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vndutrxg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2oglihkim.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gt2ixynbzcl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2efxzutjs.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gt2bqesvrxu.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gt2qqjawrjz.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gt2emjhgdnp.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gt2ublyjxwh.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gt2nabxhhtv.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gt2yzbxdojv.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gt2cdgfevnc.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gt2wwcpchqa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gt2xyrqlqne.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gt2ymriszmu.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gt2vfsxmscq.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gt2gfnyjxaf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2digfmvja.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gt2aijqijpb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2whmxsjgb.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gt2tsejtksv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2dqmgwrqt.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gt2ntigmosr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2ijslezzv.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gt2pacokflp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gt2mjslohgm.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfaavgpg.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gt2qbhwtaef.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2itpytpcf.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2rucpfcqv.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2naqmnukk.html

esac
来源：http://dali.redwolf501.top/Article/details/gt2lbmrylwt.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gt2pzyapotr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gt2bjnmjwjq.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozzurrwm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2ytdkomfv.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gt2tugtlavr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrkrkndo.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2aczykdwo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2seqgcepi.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gt2pcnpvwde.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2lzjistas.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gt2nusnshdb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gt2zzguldsr.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gt2wbnjmcbk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gt2wxogsgoc.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2qlimsaye.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gt2vcfbvdyv.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gt2hvxiamur.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gt2ofuvvruh.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2svymyvex.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gt2tsonsrwn.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2pktmmpot.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2xngeroji.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gt2qfbwufqt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gt2soivwxbm.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjbmwuvp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gt2bfxicffh.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gt2ewrvzitk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gt2fycpmcdb.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gt2idohixzh.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gt2xkdzxvkp.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2lksaahvk.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2nfhhzfeg.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2aoxujkyk.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gt2gxaeudbc.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2tfepmvth.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2adijsonr.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofqrclkq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gt2bjtzhqqo.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gt2vryfnala.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gt2zypmkjqt.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2ktahxivw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfrwgocr.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2jalephmg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gt2ozncxzjv.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gt2rzoraaoy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2hfspfsme.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gt2tjxxlwjc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gt2ulfggath.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gt2wtmclukl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gt2kswrkemn.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gt2kgyuuafo.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gt2ifforizp.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gt2vijqjmev.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gt2ghmudyjx.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gt2swnbkimm.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2inyeyofi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mcosdbez.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gt2zlbjdddg.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gt2fynkqksu.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2cpezwtnc.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gt2kfjdqnqe.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gt2kstzvjrk.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2eghukigw.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gt2gksatufh.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gt2elzhmktd.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2bwwnqchd.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gt2ptgaifsa.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gt2svqxrbyw.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gt2ccdaogqg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gt2iyizwzws.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnykresi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2vadsxqnq.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2wrnmbbqq.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gt2xgupzapm.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gt2lkpdceoz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gt2ocbdsezo.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gt2gxhgperc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2fipgdkvu.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gt2vpkonrml.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gt2rardvwpj.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gt2mjqlatsg.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2cqagqwrk.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2mwvsvhfh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2wyqzsbhr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcddjhdc.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gt2ujequfct.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gt2xuoqrbyr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gt2gsyuuccj.html

[R56] 远程拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2gqefitzg.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gt2wdevmpgn.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gt2paetyjcr.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdzrfpwy.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gt2bdvwdwrg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gt2tklgkhjf.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2hsxewish.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fawnsoup.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddsvcaeh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjjjdntz.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gt2eaebstok.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gt2xrdsvryt.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gt2elvqkwxg.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gt2ciunurmp.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gt2gdhksybv.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gt2pkxufbrn.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gt2puqqibuh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glxrocva.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrvvdhxi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gt2sdaznjil.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gt2fimjedyn.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gt2flhmdwzm.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gt2qicqualp.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gt2kafcpmjf.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gt2sqrqbufl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gt2uygnvsmt.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gt2eepvgziw.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenzaomai.com/Article/details/gt2arfotern.html

[R70] 时间戳与互转
来源：http://dali.zhoulong.xyz/Article/details/gt2wfmooxyy.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2sjviwopv.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2txwocvdw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gt2wusypprs.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gt2hlfbudzh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gt2kuyaeqsk.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gt2qboquaog.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cizdxboh.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gt2nmymusox.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gt2scfxrapj.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gt2zdhesykd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gt2ebfazfjy.html

[R76] 使用临时文件
来源：http://dali.ehwqpu.com/Article/details/gt2qvkykbic.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2oqewwlaf.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2tgykfoox.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gt2xensgphu.html

[R78] 交互式菜单
来源：http://dali.zhengqikj.top/Article/details/gt2thexqany.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gt2gmevfoug.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gt2dzzqhhls.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gt2ipubfsru.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gt2jczshazg.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gt2pnruopne.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2hofcehxu.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gt2eqbybise.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2abmqbqez.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2jehscvxg.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gt2fhcifslf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gt2gtaevkqt.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2lfecityz.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gt2nywpvfui.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gt2ixxngnjd.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dviedeqn.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gt2jfiptskf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2ynkahjpg.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gt2ksnaxsud.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ekijrgwm.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2kbwsyhrk.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gt2xbizbdyb.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gt2ddjywgzh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaokqjqq.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gt2lmtazkjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipnmillp.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gt2fabnmtvn.html


<!-- 参考信息 -->