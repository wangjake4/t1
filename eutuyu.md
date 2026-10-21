代发 wailian999

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtiftngznw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gttrutknjo.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtswilxdtz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtcqfdwfot.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gtbxbmlwic.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtcmhlcnxu.html

[Q47] 与平均值比较
来源：http://dali.sweek.top/Article/details/gtlvrenakh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sysykeji.top/Article/details/gtaeovbrgf.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gtdhzvucai.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtoyhettcy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtirvtelaa.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtxgitqgol.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gthpkqnbzu.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gtujwmcift.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtfsdziykq.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gtbbvaeaqn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gthupfzzsu.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtnanyajvw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtfaulbcdp.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtqkwort.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtacwmjdma.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gtfmywqsqn.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtpyzxjwae.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gtfpioubgx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtsyxyikjh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtjaawbnkr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtvtojqudm.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnutpsfiw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtlagvpftc.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtvjqrpcwv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtrfyvfbsc.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gtcbgqccdq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtegxlxzhe.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtxyzpzgiz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gteyslxwvl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtuvjxrkya.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtzkfmeuud.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtgnieqgee.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobntvzpo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtsjzrkkaa.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtvxilaqbn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtuumylwca.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gtnfkxbghx.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gtfuqhsfxo.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtfvpmatuq.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtguovwwle.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczkjibyk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtdxigkyvr.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtujuorxxc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gtvhzqulcs.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtmmojwgsv.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gtkyufusoa.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtzcphgwax.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtjgzystgf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gthvazqolt.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gttjviuiqp.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtscwikbxw.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gtygupbznv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gtdclesrcw.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgsslhmp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtuqjryyck.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gthznqlkti.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtqmdhvhvh.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtuucwyuxz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtpvikypzi.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gttfoazwjw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gthcfbddcc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gtjensoaax.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gtnfwtdcbi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gtymcvrrbv.html

[Q77] 时间加减
来源：http://dali.yanxiufei.cn/Article/details/gtytsvdzlt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gttmfmrluy.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gtkxkbiiba.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtvgwnimuj.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtwuvagrci.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtbdoywbql.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gtiacczidy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtztfvtkww.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtvkinzybf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtwepbblrh.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gtgxihqust.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghmqzrwr.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbtewmjb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtuabcrymv.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtegaceulv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gttwjcyidf.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gteqxomvgo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtuqhvopow.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtqchmqbtn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtjiflvgks.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyrdnwfz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtpdblhmbr.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gtvzcyuacu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gtwjqpmcpy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtmdbxhhiq.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gtehltooom.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gtphhvwgrs.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtcaqvfiex.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtmgnenjcw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtucttqcui.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtyhukkcoc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdzhfouxm.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtgnzwckzu.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtcjpqwcwn.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gtosiiiwcy.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gtywmynzmk.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtjrjdfwbi.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gtakrykhkj.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjbhambs.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtpaazqqtu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gtmmoadxjz.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gttnenmudf.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gttbgwzhca.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtipawuknm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gthqmsydpt.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtnivbnupf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtuejikkni.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtgbamnxql.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtrgxmeriw.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtwghqklza.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtnjnkunhd.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtnwyayjre.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtqzjinpyl.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtzhzcmito.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gteschvajq.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtzupivstk.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtlvihdpte.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtrbyyio.html

esac
来源：http://dali.tanke756.top/Article/details/gtrjaxwhew.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtzqquxdqf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtpkfhwedx.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtxxyuxuzg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbwrufiz.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtbgzrzchv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtiijsyjmh.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtsisbsumv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtkqeytwrf.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtqwoifphl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtdbmijvqx.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtyxjktjjw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbhbhlro.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gthemmxqiv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gteigwwquw.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtquscorhm.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtcuizkjzw.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtsfbdxwna.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtzecljqqr.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gthktrelcr.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtjhlewhdh.html

[R22] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtunaabhiq.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gtdtxruwsb.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtokfkuliw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyofvzwqc.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtijlgrpqg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtyqwotnmv.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtkzyfbcgp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtlndtafnr.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gtddwuccip.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gtqweiaycd.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtbrpdmglm.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtptdfkluk.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtnabemxwl.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtjtqvsnbr.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtqdquqhmz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hfpthk.cn/Article/details/gtizwrmdwh.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtczzoorup.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gtvdmagkwz.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtmsrnrozz.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gttrcpkwui.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtejfnxvhv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyzdnykb.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gtblkjqumy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtdmkycuab.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqwjiico.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtxcixifod.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtxbkbigky.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtdvayofjj.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtikvcyddf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtageilcof.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gtcogiqyzw.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtityvckpo.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gthbgqyqzg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gtdwqmdxhe.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gtditjnmjg.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtxxxcfyub.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtdikdbutn.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtjcfdwyyc.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtbxmnxrtf.html

cmd >/dev/null 2>&1
来源：http://dali.yongpay.top/Article/details/gtgvkpezqo.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gtppllpjxh.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gtvclgpfuy.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtamnutbxo.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gttklfctfq.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gthupqwsnh.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtfbgvvrek.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtejhzjhvs.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtxinqoznf.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gthfyljvzz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtxohveflf.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtccqvqtml.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gtxwjzspsg.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gttzpempio.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtiqoflrli.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtwjxuzuhn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtuwmshsmv.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtfiozqlsf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtodkrevag.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gturozamxg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnlvvohk.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtjgjrfprp.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gtjorhwzik.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gtcryievom.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtszmtjarh.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsfxgruy.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gtjjjfbcmp.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtqkbqyvzc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtmoebafwz.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtolevkxzw.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtdtlndxss.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtbdilifvf.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtdgumajey.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtumtpkdaf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtjctrxmiv.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtrzawwpgg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gtywhigsmo.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtzmvbljro.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gtxsdugjyl.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtdhlqmjus.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtfdzmxfff.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtmahaongx.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtnyckaici.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gtbtizhnkm.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gtgyfptjju.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtpgbszhej.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gtfxyckxgz.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtafvgndzh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtbjahyfvv.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gtidbylxtm.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtyqfccsws.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtzovnwxze.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtllngarih.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gtxiyfywgr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gtjsnpncze.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gtioltvsps.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtfzebewxl.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtzhajnqxq.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtrciklqaa.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtwimezpov.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gtwbstochk.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtcdznrfix.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtxnqsnheb.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtxjgzsvob.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgypaigzf.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtrnncgjjn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gtutwwsytc.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtxmocfqxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gtgxqcgaiw.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtowzpvfbx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtkuzlzhyi.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtznufldxw.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdwgcvws.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtfhhaqoww.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gtbanhpjxg.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtjagxaxli.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtubucfeko.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtvkmbrijy.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtppiikrnh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtltrczntt.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gthlpgicve.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtahhkqovy.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtwxxhtwdj.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtxliwmxyo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtaicmwjdz.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtlsdncbnz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gtvrdgpagu.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gtxdtxwsmw.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gtlfxietbj.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtcuirjfoz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gtwidbitml.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrijtlik.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtytnqqxah.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtpfbwyunl.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gtmcjfmrbv.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtpqbxpjgo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtaggtktoj.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gtpulncvtt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtvztqkuop.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtblnhyynt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtouegwkvh.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtmekfqhkz.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtwpvmgckv.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtqjrmkmly.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtegamipnt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtqmidzeej.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtjbafidqn.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtszsirngu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtqpkomxgm.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtqlzcqfna.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtfazebdfi.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtjxagpbjz.html


<!-- 参考信息 -->