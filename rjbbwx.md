代发 wailian999

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtcueikneo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtarawhedv.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtufmxjcty.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtpiikuvfm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtitillafx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtwepahude.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gtrmdjsawn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtmryxnrgu.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gtenzlqheg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtgfoimgok.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gtjclsnjhb.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gtpybhmfum.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtkwpsiugl.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gtuaeztmnj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtufmxwxox.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gtbbkijtat.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtvjndonjs.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gtxyycsgcu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtgymdurul.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtogtqougj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtabvdfusf.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gtvhfoevip.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gtqdrwhhys.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxpcnrds.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtikhxmdrw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtbamqhpen.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtwwctfzfq.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gtmnapeuwb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtqbpppbqr.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtcbatgsnc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtcykcnrqa.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtkooacbvj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtcodljdto.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtlzcwhovd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtvshisidm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtcpfmcisa.html

[Q61] 移动平均
来源：http://dali.zhengqikj.top/Article/details/gtafxjsmfg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtjfllpavg.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtszblubec.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtbnpmrmow.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gtalnibklg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtwldvhjul.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtoxvnfhuv.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtghaxubrb.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtahkgfaop.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtxphdguem.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gtipqnfedr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtbkuauuwc.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmthmvta.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhafhrak.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gtxuuwluhz.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gtancoxkzp.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gtzodivpbe.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gtxgvlgfbu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtrdcylnwb.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gtqblwxnea.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gthyytszug.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gtwtsbpwbr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtqcinxvqw.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gtkobimqgv.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtitoixksv.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtmzbcwcbe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhhvlfqr.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxdjgccp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gtidjezuhg.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtsgdwdadk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtztfqfzvk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gtvmftwoyl.html

[Q76] 按天统计
来源：http://dali.shangyingyoupin.top/Article/details/gthdreskin.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtoqvmnssu.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gttyqrwypc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtncjheeig.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtxmxnjwvj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdnkovag.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtlujkejuv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gtilxyyisg.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gtilmvpcbz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gthhidqxye.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gterwvnwfq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gturrgvrau.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtsczrvgjj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdphbtbvx.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtubykgeck.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnyyjcny.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtnfhdvmyu.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtelixbzal.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gtooipmgtv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gttldhuwjs.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtlrcilrec.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gthensbqnb.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtgxhlmnhf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtiujozpmn.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gtnmrwtuel.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtkpclgirw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gtssneavzk.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtteszobuo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtrbbantcl.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtaesfzifn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtkjnibmty.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtviwvvkkb.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtdwpbpmet.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrvuuuzgg.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtwzmcvgen.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gtedxbfaaa.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtxtscwrhb.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtmtydwvnm.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtyzlvijdd.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtlrvzzqup.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigrmboml.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtcfrwsbuj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxxrogns.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtshvayphi.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttxrmjwoh.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtxwdfcdcv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtbsylvigl.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtodqaixug.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtmlxkbkrs.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gteywmtmir.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtjohteiec.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtfongtdet.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtshkdibrj.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gthlvspyyr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtffqzrkxq.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtippwgyhu.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gttklmyrnx.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuftlszns.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtpeujtxrr.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gtffimvxhc.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlndiome.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtsjygmsin.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtcgysblky.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gteluccitp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtfcmokiod.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtazdtgjcf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gttddqqmqw.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtnwcjralq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtwowefkdl.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtzvbaxdnj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtstbyqxmi.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtpmimhjso.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gttqpawkjv.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtqkcvwyoo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtibtbjqck.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtlksgnjac.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gthvjmoqke.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gtqqisyxxd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gtqimozawy.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtxglxwqxx.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxvytgyc.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gthizyrvxn.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtbgfxiply.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtpiwcafny.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtasgfgxuq.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtzaxexstd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gtpgelpbmt.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gtmuajqwqa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtzforodas.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtkheooqcp.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtjehrfztz.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gtwgtzwcaa.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtmyesrjhw.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gttmkbqdzw.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtomqiehgu.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtijezjtjt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrvrpbro.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gtyozaetzx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gtqwezxqmu.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtwvreeijn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtpkvzxyot.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtwoviqnhg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzmmrsqc.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gtoqyptclu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtixlqklck.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtbidpxhkm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtbyzljzyf.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gtkfckcvrn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gtcimmneku.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlsrcxpt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtmsozvkzx.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gthzvimjfk.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtuljgoqky.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtnieuymez.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtnkvuheri.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gtpbeeqlje.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gtjjxoqyyj.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gthyevihkc.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gtqpumlvik.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtqgfjzrzx.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtfhghgnlo.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtfvnycnpr.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckiserpx.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowirvoix.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtlzfuerop.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtnsgmjhba.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtpdtoxeac.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtrerhjlml.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gtyxsubpyd.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gtjshfmjit.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtsadyjjgo.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gtazgwgfku.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlwkutly.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtatwrullq.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtabtduqfp.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtvjraibco.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtedpsctuv.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtidfxeopd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtkilpzohi.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtrbijljmq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gtbuvdogwn.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtnobggpuc.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtckjtznfg.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gtleulcmro.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gtpxgmisrt.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtzijfmzdc.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gtvfauzyyn.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtkjdpakig.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtavzfqwyo.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtqqxahlaz.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtwogwvuui.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtuoksunpg.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gtqcwlolfb.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtyeddeeua.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtexsooajn.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtbcoatxoq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gtwvxidnqd.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtvnglqslj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtxfuavlsu.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtjrggywds.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gtkuqrxadt.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtxyronval.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtwmfqdxto.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtttxmdcej.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtskwezkog.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtjlhgjlsk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtyznkzywm.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtptfrqfou.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtgffnroqc.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfteaxyr.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcogxpecz.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtcmypfjdq.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gttxvrkywe.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtccntbmjc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtrtgycmeb.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtapuavbjd.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtboeqovzi.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gtanosdwnl.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtfgoabkmb.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtfwaopcwa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gtvtebvofo.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gtgksvgowd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtxleagtbu.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtxpzafsmq.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtfhqjlrju.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtzamwyhve.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtcaziaokm.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtrxgiitsl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gtnntrqhty.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpanmreyu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtdlxrtzlx.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtwgahbkwi.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtrhexkwpx.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gtyoptggsp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gthmynrgjk.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gtyuilqcca.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gtgjabdrno.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gteveuuvjm.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtqusbkogm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gteenoixbo.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtwejfpouy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfwfbhrcd.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtwirlmvnq.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gtdmqsxofe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtdezbprgy.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtwwgkguas.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtnviiqoqk.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtjtyazmdx.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtnobdohjn.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gtpbtsfotx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gtamdxgbga.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtykbsczqw.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtqrkafi.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gtcqezvklt.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtwurwgsbi.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gttbodnlcd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtmcwaktap.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gttzehoiet.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtycajumla.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtpmnszxcl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gtobbnyqli.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtivcwgcuu.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gtntnarwrv.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtmjiseejm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gtotqszxkp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtdiqvzjmz.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtuhrmqhto.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtgayyqlat.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtimxmrhoh.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtsepawojt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtzcpaybvm.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gtjzkwgagv.html


<!-- 参考信息 -->