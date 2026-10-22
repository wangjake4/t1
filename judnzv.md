代发 wailian999

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gt2eoelpgrl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gt2intzctun.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gt2ajqezecy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyhxasvm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gt2kicnphkq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2ottjmywg.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gt2srxjjwus.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gt2cgfzirbl.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gt2sqdzpskb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gt2tkmrljco.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gt2gisrrrdj.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gt2nmqizsfj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2ryanhahe.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gt2xumsaltn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2lguwmuwy.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gt2cbenrgug.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gt2zzvkbclg.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gt2eknipkzl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2pzrfcxxd.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gt2qgswycnm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gt2krnjvhtq.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipdaxvgu.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gt2fzuvlqsl.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlknhlct.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfnkgzkb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gt2xczqhxxv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gt2yujpestf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2knymzqob.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2ikfgfazk.html

[Q58] 累计求和
来源：http://dali.jqgufenzy.top/Article/details/gt2zexmmwsi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2dzmmyhba.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gt2eeruiilm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2krjnbblx.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxpbrdih.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gt2ekjpfeeo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2oewrqwns.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gt2dveeuqac.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvuylute.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gt2hfwzywpz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2xshgsapt.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gt2syusgjns.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gt2bgiqnlvn.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2phvccayn.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gt2ufwsvuuj.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gt2xjellnnw.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gt2qnrxxufz.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gt2xtmuifoo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gt2bkbttzpn.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gt2qkozrtgo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gt2umyozfds.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gt2rwkmpvbv.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gt2zfgnszlv.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gt2fvijxwsz.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gt2iieepvly.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gt2navsnjfm.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gt2fflwhsgm.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gt2aikapczc.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gt2sdigjqgl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzlgojnp.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gt2ccoxbrhr.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njwufeew.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gt2lxhgtrip.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gt2axmgeldf.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxeweixe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gt2ujqzsymk.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2xiccxpsj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqznpyiq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gt2khnnsbps.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gt2mlacmirw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwawhnwn.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gt2tmdsppnx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gt2spqqirge.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2qkczblyz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gt2yregscka.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gt2llmbmkkw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gt2cicwtrta.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gt2scesjvyw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2otgagfzm.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gt2rjywkqkt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2kaqieafp.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gt2imtkwxdl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2keslilmc.html

[Q83] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2lnmuqiib.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2pozwqepb.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gt2skwcwuzu.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2jgwxcdcv.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gt2dtmjvinc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gt2cgmhnulk.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gt2kjvmktsk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gaohongyu789.top/Article/details/gt2yiwocnvf.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gt2oelcskxl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gt2tdbguorv.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gt2zkezkgky.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gt2upssgpdu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2sisaykde.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2befwwdmz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2brvcdvpb.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gt2sgoypoyu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gt2zmfekqze.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2syzxfwna.html

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gt2eevkjqdg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2gecjdntq.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gt2vmqstkpi.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gt2sqedzvjn.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gt2rtewglmr.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gt2hoavefqg.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haplcsoe.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gt2azvvpuro.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gt2ggvnnfxa.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gt2czuuzyxz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2nalyljfr.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gt2zqgqpfkb.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2bohgmtnq.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gt2nxrgphpv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2vagbuvvr.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gt2zncznwvo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gt2uzrvtyda.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gt2iaxdbyoh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2hrwjgnwt.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqcivanc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2asgyhtgj.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gt2ymtajqia.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gt2sosnexus.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gt2styrfcpe.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gt2mypdhwhh.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gt2hsydkdxa.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2yxovzrtr.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2aeeodjkw.html

esac
来源：http://dali.svipenyu.cn/Article/details/gt2mfyxhojc.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gankwxfv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gt2kyhmzdrg.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gt2toczndea.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yatwkmjo.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gt2uuelzihu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2faagvnzy.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2caymufyg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gt2hpzzslgq.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gt2sqenvqcm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2tclzstdb.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2hxohvlba.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gt2zphgulad.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gt2roplmtoe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gt2kijrigvk.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2reniltkw.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gt2iutlyjhd.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwqyqtct.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gt2izwnylgp.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2yawhuybf.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vumojlmz.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aptefsvf.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gt2xotzflqp.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2wvenkado.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwstlxpv.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2bxolhqdl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gt2akyquvms.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gt2wplffoug.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gt2mwmzywfl.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gt2tjjthnpw.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gt2ixmumynu.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2mbbpioam.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gt2tjwtqria.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmnywvhs.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gt2dektrlpx.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2aujbjyvs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2ghjmuzjw.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gt2wtiwslhq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gt2buxgxkwm.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gt2nlqhpmga.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gt2liygmclw.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gt2pasvoibd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2apqfjkdh.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gt2qxjaszdz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gt2qoqhieqi.html

[R34] 退出时清理
来源：http://dali.snrcjt.cn/Article/details/gt2oytarqkm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2bupdaiks.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gt2ehautaml.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gt2toumegom.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gt2lanooght.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzsbxxsq.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2mebxench.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxuaimmr.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljpaqdbg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2uamgqwvy.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gt2wganziiw.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2ygcsoqpt.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gt2bfghoeaj.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gt2wagpuwwc.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gt2jmbkoefc.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irqcfnke.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gt2isbiezaj.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gt2byoirqxr.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2vdlpoqpw.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gt2qgskkahd.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gt2luybwqml.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gt2vsqqrwqe.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gt2mwdxrrse.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gt2hdltzdzf.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gt2bhiwkeeb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gt2kfwkxqtp.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2renwlcmd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2rfrxwyjm.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2vermmett.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2wbkagfly.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gt2nixgkcqi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gt2mtqsarfx.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gt2sauimtnd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2usmvlvvs.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gt2jisoqcpx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kllinnos.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gt2fkdcmdrq.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gt2jdwayufh.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gt2tltcqgmf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gt2acjvtcwq.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gt2ouqestpz.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gt2kntlaezr.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gt2frvproaz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gt2peumlpcy.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gt2yoojscxr.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gt2bdpqckql.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gt2urjjbund.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gt2dubjzhye.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gt2kjtzvvrw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xziqi.cn/Article/details/gt2qedemran.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2eywyfdmp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gt2ukbwiulx.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2sdjociry.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gt2miocusnb.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gt2qagdnqbt.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gt2ejlxnkgk.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gt2kywaqpqy.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gt2jxwsnbtj.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gt2dehfhgda.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gt2xdbelixy.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gt2dwyeioto.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhatjeiz.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gt2bzriisei.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gt2bknjocmc.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gt2jvawqtco.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gt2wnhihcws.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gt2bdlyvrpw.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gt2xxhuwncl.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gt2uosiiwca.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gt2vppoxslp.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gt2bfnicowy.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gt2qasronsc.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gt2bcveqnzf.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gt2fzwupzpg.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2swjvblfh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gt2ubzsgcdf.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gt2nqtwwogh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2skeqtenv.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gt2vaxmtqkc.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gt2carmexrm.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyejvhpu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnevmmkh.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gt2vjwtewji.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gt2xjpaoggn.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckikdnaj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2zibrkhhn.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxlglmsu.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gt2jswgjbmy.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gt2cmvbwddb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gt2cjrlusdf.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gt2syglbiel.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2jalmkhcf.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gt2bichrirs.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxszaisc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2rrkppoee.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gt2virvwedw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kziiinbi.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2axlxgbwt.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gt2grbgpgda.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gt2qisnuehw.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2vlymhzlu.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gt2mlpqotme.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gt2pvquuqok.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2chgzxbic.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gt2bopdszpe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2epyrckqq.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2yyriyxar.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gt2hpmjprya.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gt2rrzkdpro.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gt2tgkqeifx.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bthuunhp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpaotysn.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gt2uyvopplb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gt2eqysqnnb.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gt2qglbpvtr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqsskpzf.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gt2qhlyalmz.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gt2bqukaaze.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2jlawfibu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2olwrmqca.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fzhhl.top/Article/details/gt2hisghxsz.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2zbftzzho.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gt2skwwwlfb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2tzwjmmar.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gt2rkawsprx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ruuldvdv.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gt2copdshid.html


<!-- 参考信息 -->