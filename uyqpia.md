代发 wailian999

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtqzlysmcj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gtjgpesrhz.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtlnzsoctj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtsgwgdqoa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gtpvjlevdq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtlulgijeu.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gtrkkjnytx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtkvtieurm.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtlqxjewyt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtvyxjiuyp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gttgmbpvvs.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gtqekhweam.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtjhxaigzn.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gtkvhprwoi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtlvxsrpwl.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gtakhsuygt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzuhxfeg.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gtsvgbjzcw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gttbgdqeqk.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtflsnjzdd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtvwypwmeb.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gtotcqgujd.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtzlqzzgdw.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtzktfwizp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtnhjtyszr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtplfqrddf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtilbmywwm.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gtvdwmtzha.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtynvletcm.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gtnzmobfhh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtshhpifzj.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gtnwvnvgpe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gthhbguoam.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gtghpntzms.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gtkoiutmed.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtgfthueda.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gteugyfzkj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtlknflhhw.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtwqmeawwc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtlnjrncdu.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gtbqfadwiy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtcbojkhdh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtasbgndah.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtxhobjnbs.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gtpoifgjna.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gttegjybeh.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gtakurwugl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtedlfhghv.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtljqyzezf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gtdusrudqh.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtrdckzyjr.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtsvygtvph.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gtyqzwcjgu.html

[Q69] 查看执行计划
来源：http://dali.0kj1m.cn/Article/details/gttoeamjdp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gtfxfrjhwc.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtpkzoagal.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtjbasmzqq.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gtitohrurl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtohcpxfbm.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gtafpuggmh.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gtjymynhsc.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gtrsffulxd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtrxslhedk.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtexfpkzay.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtsmclpizf.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtnivsaeie.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtpcwphied.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gtqyxddsdo.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtinxuoiqn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gthppkrsvi.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gttvrdhaqs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gtijepivah.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gtadpiavqi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gtikmrghaw.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtitdmknmm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gtewlwxjqm.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtbovcrzpo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoeaxuyy.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gthzljwdfr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtjpaimfxk.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtujpvvvbb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtpfzdjdtv.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgutcrzec.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtsbeqfpng.html

[Q84] 去除首尾空格
来源：http://dali.cdnleiting.top/Article/details/gtqxnejjkf.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gthomoebpb.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gtqpjhhlvn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gtmxegljav.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtjwpciqbh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtktmbvjnb.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtpgfuyqmj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gthrjhkzet.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtptejljpx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtltboshpg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtbmugygds.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gtzvgneqgu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtayjnpkgv.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtouumtugd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gtycdvmsdj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjcukdjl.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gtstdihotb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjmffxisg.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtrchbldwr.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtypkezvqy.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtptjfqlff.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzkxjiec.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtletrdslu.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtueupbghw.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtjtwrjmui.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtpjxyikrb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdenxsvsu.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtphcoaqge.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtzekckbty.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gtdlnawimq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtdnbjlyjx.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gtvfupjxez.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtglwrrjyk.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtlsfspvza.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtqgeczbzn.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtwuyltkmu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtjizwnfkj.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gtmvssrnqu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gtvaxjvzcc.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtfncprgze.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gtmnqkmuwr.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtqbpgxedr.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtmvqiftpp.html

*)     echo "未知命令" ;;
来源：http://dali.yuxming.cn/Article/details/gttvgroijn.html

esac
来源：http://dali.sysykeji.top/Article/details/gtnaavataw.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gttksgbadv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtoarswdqj.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtqwjwyhwt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtgormidxd.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtquevpjxc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtwrpwaibt.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtoeysctff.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtfyqimuof.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtkamzgdjn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtcerrofum.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtxmcesewg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtilivgldm.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtrdtbxmzr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtckbhuejk.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtcynsvjmq.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gtqxonzvws.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gtzvzfdjot.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtbvpwnctd.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtgqabxwhp.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtzgmilsch.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtexgqcrab.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gtmdspeawl.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimmttiyx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtdovmptnn.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtadpfqqsr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtabvjukls.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduokdgrr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtaqcqllyr.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gtiyjbtrtv.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gthgbweqev.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtphypidfd.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtsakfpvoy.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtsjoixyft.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gteamekinz.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtsbcvuioq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtitzekhij.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtvlsssfmx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtojswsujw.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtwmuecbho.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtcxijfuek.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gthhewwlzo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtonsyamlq.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtbfgmabdc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gtnyntydok.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtinwswaan.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtxbsmvjai.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gtepqotuuk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtwikobipn.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtmerlliks.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gthsganuzw.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtzhhuhqjg.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtyoguatjm.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gtfvxwrbhj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtmscigxml.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gtxwcrvlyv.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtxdanoywl.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtiabznpai.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtnunupmnv.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtncsnoihi.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtnvwwwpgd.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gtkxcrdxjr.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtjseyydyf.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtzglhmowk.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtxdcifnmg.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gthqkznyga.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtamefcgeb.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtzzmhynzn.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtjnohaepf.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gtmegbhcld.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtkorfxvyo.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtzofdolbw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkcfchbw.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gtkitlfgbs.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gtgmjewlig.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gtxkeenhdg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtpdvprrbj.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiznjtsn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtemdnphny.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gtvilbupla.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtyqprkuis.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gtoevrgspo.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gtflymontg.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtnaivyrhm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtqidkwwek.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gtyutxttic.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtzeaitjel.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gtauppnrgq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtrcfgvmpm.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gtrspqamku.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtclzgjiut.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtmmxcwuwn.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtayloszds.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtnggwtslf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtohxnreop.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtfniysnfh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gtxwhmoxou.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufmojlvc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtgfwbrska.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtrgovijnl.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gtbwledtix.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gtuufumldk.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtwefetdsl.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtawnasyls.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpuzmika.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtacojyccj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gtncwbwyjm.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gthirpyfgm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gthzgoddcp.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtyczsbkus.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gttezrhuub.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtbuoigagw.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtfcmygwdc.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtuxhubzzo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtlpzdpqsm.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gtatafdajj.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtisljxkge.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtsaftnvhd.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtxxxtbvnn.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtmsqgastr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtlflemtbi.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtxhrcppzv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gteafgjnzs.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtmhyvxjfb.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gtpyafoyyt.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtckamqypc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtfeumyvbb.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtybbrpdww.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjravqjf.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtnxdhscip.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtinilvevf.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gthfobtenz.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtiwqwwntm.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtmuvedgqo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtdbwlaxwd.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtlytdgpox.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtboddaqyn.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtqphjwsxx.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtvtgqmlbj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtanoweqzg.html

S. C / C++ 专题
来源：http://dali.yongpay.top/Article/details/gttctjefsu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdrkhlhui.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtsuelpnnd.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtnlcaogqa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfblsbjw.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gtwrdlwvqt.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtumihluzv.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtkjtsotoq.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtnbxnqsll.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtbgctndjg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtdgzwquhj.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtuqzloqtc.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjpkapslk.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtnbdmoikv.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gtgnzcghez.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtykmyodvy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gtjlevjdtv.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtznrrrdnf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtkavzzwvf.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtlntzaamm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gtwncdmdfz.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gtrecbshic.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhinnexk.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtavofnvxa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gtzsmhiywq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtbzsowonw.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtbaxprroh.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gtehikqchb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtihlymwgu.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtkwawulfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gtigmmcoul.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtcxktnnxv.html


<!-- 参考信息 -->