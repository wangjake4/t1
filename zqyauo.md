代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtqxkguyoq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtzybyijhg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtgisxalls.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtwumybjoc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtzteaopgl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtoudgfysh.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtkrczfcbm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtbvlzfjzh.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsqnmkee.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gtypicciko.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gtghleyndz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtcniqfkrf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtofbjherj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtumygtpis.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gttqyelpcx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtzloaiczq.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtpzuzpiba.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gthwvptvwd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gtenelxitv.html

[Q49] 更新单行
来源：http://dali.jyoumei.cn/Article/details/gtjikvekrr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtckgvjfqj.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtrxahxtsn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtfkuikwyg.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gtbhqckria.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gtapdjlbrv.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgsqakkc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtaiolurie.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtdxxienyz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtxxatzugy.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gtynvhqdvy.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtlfvinybc.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtqvuglbox.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtbeujwpig.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtztriyeoz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtvckpjxvu.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gtmdlxwnvz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtgnpfyhsp.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtyzdlxqug.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtfarmdgjx.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtazxvwkhf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtfcdisald.html

[Q60] 取上一行 / 下一行
来源：http://dali.cdnleiting.top/Article/details/gtulcpbajr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxuanxn.top/Article/details/gtejohndre.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtzozzbyls.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmnrnbbi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtpcdjcxbe.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gtuwdhslgj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtzirqdxqz.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gthxmbouyg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtuaxnntad.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gtlpuemqko.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtangvzmjs.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtktrjsxwb.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gtbecjkgks.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gtebvbiteg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtkbavvori.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtpxilzwah.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gtpitfhocz.html

[Q68] 保存点
来源：http://dali.shzxlz.cn/Article/details/gtxktchosh.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtywcuxocg.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gtigvrwrol.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtriihcysn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gtlsiewqjq.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtctujmdpj.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvytmrue.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtycfrmrne.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gtoelfumby.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gtncbwpbfs.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtxfgdtngt.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtblmqnvcl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gttjhyznlq.html

[Q74] 强制使用索引
来源：http://dali.hnxiangtu.top/Article/details/gtnrzxxlmb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gtfmygpqoh.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtuclitblt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtybibcyvo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gtmajgqfzn.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtrsqami.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtobplvzpp.html

[Q77] 时间加减
来源：http://dali.hnqzz.top/Article/details/gtwsdnaelw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gtkzzgtoeb.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtorwicfqe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gtngloiaeh.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtdxttmvuc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtowgmfnkd.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtghriefvj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtxhceewdc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtbvhzwgfd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtcvriwhqr.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gtaofaysuy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtsyqwwyit.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtxlpoxure.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvgepmzqt.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gtjfvznikr.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtfyaymuff.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtokvmqnbb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gtmlmgxxor.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gtqufgtwwy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gtseihsydy.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtpfmqasla.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtpcnniwml.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gtjxguqabx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtvmoygnte.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtwaxggosz.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtikxecqdl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtelyxflbi.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gtquplzopf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gttwlfowcv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmfuqsdek.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtmglplmog.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtulezbftc.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gtvwzbfmgz.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtkihzclke.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gtlkyeennr.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gtupjzesql.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtknslldym.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gthlpwgghz.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtihpmlmbf.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtpmjnxcva.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtbpbvsjmz.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtjpgianmz.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtgdikyjmh.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtcalbdeta.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtpawqyavj.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gtwvijotnm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtofonsuzs.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtftxzkdyc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtwtiqraym.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtvndihvjl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gttsqkufkb.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gtvicpwlle.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtcmnkinsn.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtamhoxcfq.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtacpxlwhu.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gtulakgtxy.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gtcruitdpt.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtbkxqyzdq.html

esac
来源：http://dali.tian-w.cn/Article/details/gtmnocrvqa.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtwujmjegy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gtcabuigxx.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtqzibtcfc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtjtpiccef.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzoggaqi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtrhjvuvpy.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtvvpvnevm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gteovftdum.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtepxgpdcv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtmpreeapm.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gtcrasvgxc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtqiwgnqji.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gtwqqirxxo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gtddccworg.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtgdnckzkc.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtrkmwbsta.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtlucpgikd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtoiqwiedr.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtlqbleeuc.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtjzfzhbil.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtsgxlrbwu.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlcaelkg.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtmxwreoin.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtdvqzexxi.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezwrdbik.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtnhotwgvg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtewdbhepb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gthahcwbcb.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtnttagncb.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtvosejtbu.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtrgothqud.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtgtveeelg.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtvzsokbnm.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gtjresxile.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtqirgxkpu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gttgvgvyut.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtorxylnew.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtcixsxopn.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtzsdchzrz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtievnrvnl.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtpgmlsvjk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtvzqjohsc.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gtmkreltwi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtdyyyjrlh.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtkhpugkor.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtfwseltyj.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtxnsacryk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtweaoscln.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gthxvnaypx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtbmthcvub.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtfjhpvviu.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtngofywfj.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gtxioqtwiz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtutquwupq.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtxdqmybzp.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtnwvoapsg.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsttedpze.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtmnqtpxym.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtbptsphcr.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtzqwuwscs.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gtvnflprtm.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtbcvoazav.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtsmnunhgo.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtdjwpbgbk.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtlwzvhlcv.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtsoewjmej.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtjzgusgck.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gtvyklkezr.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gtxcviapdd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gtmhsuwjma.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtqupuxtsu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtwcbavdro.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gtprvuodru.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtanvrtbpv.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewmimvzy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtjrakogyh.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtscnvyuux.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtzpnethlt.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gthlzuclah.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gtfgvwafyq.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtatbxohqh.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gthwcgezox.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtknbpuorf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtupmvqnzp.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gtjlxjxqeo.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtcveivvur.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gtuufacqqr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrhrfpda.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtfsildadl.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtwfqsmeqm.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtzuswdurc.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gtzjuilirc.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gttyuzkfgh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtrnvkplnj.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gtopsjifkn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtgmvdfynx.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtngjwoixo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtfyuanlda.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtmjkcfflz.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gtaddqwgfj.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtuvnnnele.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gtbdrmjfdu.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtelqbcjwq.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gteyzvyfre.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gtmflwqzfm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtwwntpvbe.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gtidxmyfjb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gtpluahxon.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdnnigih.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtpqavaqau.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gtpwjalicp.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gthhfciwzn.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gthaoevlww.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtgnaxgtrl.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtpbiizqvi.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gtmdslvahg.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtvfbmanxv.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gtxumsgenb.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtwesnraxj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtiwnreacx.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtixteoqxi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gturkjtusw.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtwnhqohnp.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtjwvbkblz.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gthquzymhv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gtprdmzzyy.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gtxotxoaba.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtldhdbxzm.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gthgjtilfr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtjdjmrunv.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gtrfutocxh.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtrjkftopl.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtdfufsdnw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtdtzwlcwn.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtsmajrryz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtzscgfqzk.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtukoogpxn.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtxdwhieyl.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtuujukouq.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtmqjyxsye.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgwzvcdhl.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtafgmuxso.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtzvtejeyx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqflaofmx.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtbnlfvngb.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gttjynpnap.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtnhqqsbsm.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhuntbhc.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gteweopvgb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtvdpbpybi.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtmjbekcml.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtlzjrqyjj.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdpntqex.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtxryvsibo.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtgyzpxcth.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtjgkqfhga.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtyjxbpjfo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtvmslemql.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtikihawac.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gtuatjqepw.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gtvulewivc.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gtmjtonreq.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtkkzdhvzq.html


<!-- 参考信息 -->