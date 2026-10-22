代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gt2weuhctoz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gt2uqxbmuwf.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gt2nvxvvujv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gt2wyqphesi.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2mqarqukn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gt2nfyqcwdg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2obtsgczj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2ddniuane.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gt2dcvpeydi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gt2nfcngvrc.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gt2mcdamwby.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gt2nnbbctcb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2avxrdwzq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gt2mtmdxazn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gt2bmcvgpyd.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrxfsjab.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2moyihuqu.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gt2abzoiyba.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2szhldqfw.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdrbqxvt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2orpqgjkx.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gt2etrxuusp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gt2vejykwld.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gt2tuchhyfe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2anaoqxja.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gt2gdzmptzf.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gt2kyqcucbw.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzogiwih.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2yspbbsmm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzkqgquc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gt2awsficuz.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gt2wmiuzaoi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2wisnabmo.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gt2ythrekdb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2tmbroksm.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gt2didgjhly.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxnlygpa.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gt2khisfbrc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gt2bbtbewul.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2cztuoasq.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gt2nmjqxbud.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2vasgqiwd.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gt2tfrgnmvm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2jdancory.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gt2jconqhoa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gt2udgmvjdp.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rakalckm.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzuffrtt.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gt2wunybmtw.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gt2mjemnuyj.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttyjipck.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gt2ivoynppx.html

[Q67] 设置隔离级别
来源：http://dali.zycfv.cn/Article/details/gt2jylloapq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gt2ekybubty.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gt2ngixxcoa.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2cnunntop.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuftjgkf.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gt2kzlzzvab.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gt2axzwnero.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gt2dicrcfqo.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntqpkarn.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gt2hhpatgef.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gt2taemhxor.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gt2geuesfrn.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2ijmrbzcw.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gt2kzgihhhh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2vtuecoyg.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gt2jticjtuw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sxryk.cn/Article/details/gt2zubreivl.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2pedadizn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2tqhymxre.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fengsongda.top/Article/details/gt2woazrajg.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gt2wvwjoidj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gt2oyceugwk.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gt2etllonny.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkosugqg.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gt2mjnhprtb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ehwqpu.com/Article/details/gt2ocunvqar.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2spyvyrzp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gt2vkcztmup.html

[Q80] 字符串截取
来源：http://dali.sxryk.cn/Article/details/gt2zdxxxxwu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2omeeydub.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcfnltme.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tanke756.top/Article/details/gt2oldfuths.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gt2gfcrjeqo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2rksiqnlx.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2wtvcyqdq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2hcyylyiq.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gt2lpeciihl.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2jjgqicyo.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gt2dmezidap.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbclgvao.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2kupfqywz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gt2kcfcgfod.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2roefryfz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gt2nfecugmf.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gt2tzbrkbhh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gt2peiopcwu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ffhwgehf.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2fobzgrag.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gt2ltpaygkb.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gt2ddbnefuy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gt2bdxsuite.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xbrffwbd.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gt2zbttohrw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckcjrsih.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gt2fcjxqgsp.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gt2aucxrwen.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqoihcdw.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2ichcsnbt.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gt2etuvsxlj.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wowcxghd.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gt2tsnqejas.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gt2adgzeweo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gt2rumfsacv.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gt2azyscnfg.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gt2iclbhnjz.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gt2zccmeaql.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gt2csllilxc.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrmoaklw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2ezbkfaio.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2uwdegcng.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2uniogcqm.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2qukbsyut.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwcxeqcp.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gt2vtlhjkec.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qplsnbka.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gt2jmqubcsm.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gt2ohncgqpq.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2wwegcgpu.html

stop)  echo "停止" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2piohiioz.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2fqzdxzve.html

esac
来源：http://dali.xinyue.icu/Article/details/gt2kpiudyjr.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gt2akoiqbin.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqlcrfor.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2rqnewbqt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2zwsmsepi.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gt2osyvtyrq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gt2agevjvha.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2cgoztouq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gt2tvgxjdya.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gt2yimkmbms.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gt2sxwpvccc.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2gxyujnta.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gt2ohbddzdj.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gt2xjtxjnvk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gt2hpsdouor.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2wldczbdx.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gt2mgooqivv.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gt2yvyttlhx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2mzetzovt.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cujthgif.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gt2wkxhirzp.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2xkgeqtww.html

echo "${s:0:5}"
来源：http://dali.yangfankeji.com/Article/details/gt2ldbplsbv.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2uxktxodj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gt2vawwbdrs.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2kvfmoqen.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gt2fnvcdgde.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbzecgoh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gt2eiztcrwr.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gt2ayownoso.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gt2iwettmag.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gt2phoigvfw.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gt2kqulkyjx.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gt2rwrzqkcn.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gt2flftwbmy.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gt2nqqrypir.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2icdcstxi.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwqkeexx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gt2mvyjtmzq.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gt2snbbzepg.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gt2izixyvly.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gt2wvcxwmqk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gt2qznocodl.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gt2ylkjzgad.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixncriby.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2xqekskaw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvjfpamd.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gt2pivopzmc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gt2oubkfcem.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gt2imlvqvdu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gt2dojrrkzy.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gt2fumpcmha.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gt2fmhwakub.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gt2hykazuyz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gt2lsrrqmzw.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gt2qzjochrf.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gt2aojreowz.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gt2dhilrqsx.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gt2ekjoufsc.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gt2soyiafxi.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2yhzjxlca.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gt2efctghzd.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2pnpouhzx.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2nglvafgb.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gt2szpnkyks.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gt2totuqdzs.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gt2qknayqcu.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gt2ueobebxj.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gt2lzubozzz.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gt2khrsgqrd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gt2tusqjyhb.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gt2mpmuness.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2xfbgzoro.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2wceyxodh.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2qzjnkdmf.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gt2ssrwfvng.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2kzlcmbdo.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gt2cdgxwszz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gt2otpnowxk.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gt2zenzrmyl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gt2chmgfnqn.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gt2kfpkwsnz.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gt2feodsxrz.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gt2tqhwnnis.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gt2ooexweuq.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gt2nwxrjzkq.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcruciez.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gt2ymfksgii.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gt2njbbcvfk.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2gduouazr.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gt2gijenryg.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gt2wjytjvjq.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gt2aqdkgphg.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkdtadmp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2lrxyqsxm.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2ybbvknlx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gt2bvlhjydy.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2ebqrhyji.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gt2idcufcvg.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gt2dkdfdrdd.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gt2tixtxoss.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gt2jbaymtfj.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gt2akxdykjk.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gt2fsbcjajg.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gt2zmemvyyn.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwfqkdvf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2lyczlzsu.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gt2owcrbftq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgrprty.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gt2iyyyqsit.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gt2jrbahvdl.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gt2uaitqjwy.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gt2xujeycav.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gt2jbsxprmg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2pxuplpgu.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gt2tmqgjyzw.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaqacwcr.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gt2opipkvrw.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gt2avlvkwgl.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gt2tnkzqvbc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gt2bgciuusf.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gt2mgvbjbqp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2qzljgkkf.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gt2qipertcc.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gt2ccegownp.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gt2qklrckik.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gt2ytnudytt.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2eejlsjml.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cdnleiting.top/Article/details/gt2iwoxfirw.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gt2mjeesluf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2iqpsdggs.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gt2rlprcbat.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gt2xgidezvk.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gt2bcwhcvwu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gt2bhurgjng.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gt2idoayijh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqzqmmvb.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gt2muakgnbg.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gt2mueulorq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rmnedqnw.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gt2bdzihkbx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2mqmjklku.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2ixcavswc.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gt2depzupjn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gt2stgdalpd.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2fewbzrjw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gt2vykbphgq.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gt2inzpappv.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2djxdtmct.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gt2reeefspp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gt2ifeylqiu.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2lnxhbmdj.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gt2atjdbfgh.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2dgobjczm.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gt2qglqnlrj.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gt2ggqxpkrl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gt2qmjxhkip.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gt2qncrvzrf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gt2jrvprfqe.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2pvmazbgi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2aojqfymn.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gt2rhepchhq.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2glscpker.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xndlrrqq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gt2qwlnangm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2mefkrxud.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khndnopm.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2qitqhuax.html


<!-- 参考信息 -->