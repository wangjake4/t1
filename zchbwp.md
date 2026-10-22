代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtditaixpz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gttwtgsoqi.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmmvojpz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gtmyshdhiz.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gtrnkbxuqf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtkeilfeqa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtqyudzcpv.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gtwgwvifgh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtiiclkyow.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvogwmcx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gtagymbbfj.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtojbxhcoy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gtqkeidhpy.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtjpqdkpak.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtpvnyjtrv.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtvqhtftvr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtxmsquarc.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtopevcymx.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtyivugrxl.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gthmnvcrht.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtfwqrturl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gtpqgyzbzp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqrscknd.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyoovuuf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtdrwqhoez.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwecmcpqm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtwhjntekk.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtdzafedsl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtbevzggpl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtsfxequta.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gtfcnrmxfx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gtfwoeanad.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gtjuwaqpan.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtkgasmaej.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gtwmdeotcs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtvpwrzqeq.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gtpynjirzw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtixixuamd.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtkstgjfvw.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gtgkmripyt.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtzbthlrdo.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtfwiishve.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gtuwvugioc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtmsuzbwvm.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gthfqeiccv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtiaxyjrji.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtvszneukr.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtfujzzmtx.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtlssrdxdb.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gttwagdcdv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gteakmzaof.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gtcfwegbsk.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gttbaffmdq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gtdmgkptue.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtoqykfpzh.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaxcgvak.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gtvrovluuo.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gtrztjimkc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtfqgrbhic.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtuhydlloe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gthutyxxwl.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtrixqlkim.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtviajxeev.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtqiuoxpoy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gtkioomtpv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gtdruklpot.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gthttkdvut.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gtsfbbbtxo.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotjsovfv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gtbqndrbkq.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtehmgpbfe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gtmprvsidi.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gtyjzzqszq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtvonrxsrp.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtvfpbsxci.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlokdger.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gtrerswjsk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtnfxzjmeu.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtvlkhbtkm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtrqtzbvno.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gtgloarrpk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtaxdsegan.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtxmtxmfql.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtjkfzmlhu.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gttvdbhdng.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtxsngscci.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtrmktqfwl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gtpolehtjl.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtgfynelmk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtmjrhafae.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtogvvvymk.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gtaxeottgp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gtnmfyewje.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtjvwerfxp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtqpbebuqi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmyhbahva.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtdpnkjqqj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjatyolfa.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmcsccwv.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtrjqlemgc.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtpjzetemw.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gtsdljxwvo.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtqencqgft.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtgjybfrdu.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtnnwnhvhr.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gtqrjmwfyy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtoifeaivv.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gtpmjsjajq.html

name="${1:-default}"
来源：http://dali.guowangkeji.top/Article/details/gtacssawmc.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtztuzdisp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnvwajss.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtvorektja.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqjqtxcd.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtslsilmxm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtzmnumqnz.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gteavmfobe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gtcjiwkvbn.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gtgfgrrxrf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gtjkmasyfp.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtbfaymnyy.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gteqoshhbg.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gtorcjbpqn.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtftvwcwus.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtugigetjm.html

esac
来源：http://dali.zycfv.cn/Article/details/gteqwiifkq.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtlxsngmji.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gttnvtjdxf.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtsbxyrkqm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gthruhyujx.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtfoyhzxyk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtdwiijfuj.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthvejssv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtgybfhcps.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gtfsjanmkj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtxgovflym.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtgnamrocm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtjskwlpai.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtowgjrppe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtgmkizexr.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtvbyuqjgn.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtlvuqcsha.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtquemotre.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtwmcjkyex.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtdhvjdnkq.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gtyppbdytj.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtxpwcficf.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtqatcdvcd.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtrhzivqqw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gtqwbpmloo.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtiftjzxkc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtjvyxqwxg.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gtbwxzeuxq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtjcmyyggy.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gtmvduzlai.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtnoqmigzm.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtbnwjxmbo.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtdfqpbere.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gtfxwskvqo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtnkzvytrt.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtsdpcqivo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtyniiwddi.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtqpuifddp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtmijtapio.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtjfzudqcr.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtndukszob.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtveflrsnv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtgafatdkq.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gtndfnhdrw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gtqpmfqgck.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtfdbksabu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtgdjthafw.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gtoucnrxmf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtxwqsctea.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gtcirdxvsw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtympvxxkb.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtkmyqbuai.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhmvtrum.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gtbdgnmyux.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtfsjuhrkt.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtmwfdgkxd.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gtqpuwbjqk.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtpzraadnh.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtdzecqzwu.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gtbgcrtugv.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtuottflcj.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtrnyujckx.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gtytsaqjlw.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtaouqvnvp.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtgipffbdu.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtjkbklpmd.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtnitmcoab.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gtxahinyzc.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtxlsqfsww.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtmrxokrje.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtuwqtluvo.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtlotriqez.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtoxcxgrhv.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtizgonczl.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtguuohzyz.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtvlmfifhh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gtdzuqedic.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtetfnnamh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtnmafnads.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gttysszdks.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtodwffjil.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtuvwrsaii.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtczrnapte.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtuvfmgrlw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtmuhuoyib.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtogwtqiab.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtckmqbbmj.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtdrtjrkkk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gtmrvkyvfs.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtfuhrxsky.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gthswydngg.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtjrcoyivm.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtorhgplvx.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gtdjuzswmp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtvvvcbigu.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtokmyazmy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtiehmcyiv.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtmjovtfuq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtjoaabrpw.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtqcixzuek.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtxucxgilv.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtntnjvveb.html

du -ah . | sort -rh | head -10
来源：http://dali.smart0.xyz/Article/details/gtpwvzcsoy.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gtdscisotu.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtnjxxhacj.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtbkoehqic.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gtfyrphwxx.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtnnxhxlue.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtxaepfwug.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gtgwidtyul.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtskzzefkg.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gtndcjregv.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtlgqhdrbt.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtjozymxlj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gtftdyjhas.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtffrqwmcf.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtnbutkdcv.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gteaqbdcer.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtcuetesfz.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtchhceqcw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gtjwckithv.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtrjrswztt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtpurgrexm.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtwwdxeeck.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtsndkmaoq.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gtkbwsjgdl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtcyrtlihv.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gtqadmhnuj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtfwqxmaju.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gtfuiglxsj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gttjcwhaea.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gteaxocwgk.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gtuigiisfw.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gtmbeuupli.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gttdzfgmsy.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gtwpjqknqq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtfdfekoaw.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gtynvomzuk.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gtdehzsdeo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtomrqeimv.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gteznhvhyr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmctzyqqp.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtaahvjfsl.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gttgodxczf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjwermab.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtnzkfdojc.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtzeqfbtqb.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gthbjihwdi.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtjgyigyxn.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gtsvcmodux.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtmkwfynpt.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gtbhmovyuh.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtlvbdxjbi.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtvvpqqxlf.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtkcaqqpqk.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtwbbyqgmu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gtvyexktsa.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwefwqol.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtfgkgufaa.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtucmmliva.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtyljjwdfz.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtgqnqshft.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtaxfoftmt.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtznexmmca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtqhizqjsx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhfqrbaa.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtviduamao.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtkjaeicgr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtgwyyayrg.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtnhswbeki.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtwdrczzhh.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtsgfghjqp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtwqworcbr.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gtsntmlkuh.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtaeshqhli.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gtgwgbaolj.html


<!-- 参考信息 -->