代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtlhfyfaoa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gteyupabsr.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gttrylfzem.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gtettscfuv.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtfdujqnzy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtrhmstane.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gtlqcultbx.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gtblpyezum.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtxppdbbsp.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtabtwythl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtyxfxcalr.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gtaqrsackd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gtvnvseahw.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtbvhlvjct.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtaemykxfv.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtslblcdcz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtvfsknazq.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gttlspdqyg.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gtzfqupejg.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtzspydlcf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtaufepski.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtzlozfwhc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cashguo.top/Article/details/gtlwpunojb.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gtitrfloos.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtxajtcpip.html

[Q58] 累计求和
来源：http://dali.tanke756.top/Article/details/gtqtlmgctc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtextxlrir.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gthcmkpghv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtenipdmlo.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gtpwfvgmvq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtkmpevixo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtmgjvuchv.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gtzxtzevcv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtduervjek.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtpupftivd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtgaayqzfz.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtbbsldzcw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtqideauzn.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gtqpitgejz.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwjykwwt.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtutxferhj.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtxlaaiaoz.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtggjetici.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gtgizqtvzy.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gtujtpcrru.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gtsjmbqkjy.html

[Q68] 保存点
来源：http://dali.nwbrower.top/Article/details/gteatvcubt.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtmjnqfatl.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtuucrunoj.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gtfirqrnmo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gtqkyaddmc.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtzuwfqxzw.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gtfhvkrfqr.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gtmrgocyuv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtttsnaado.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtpazrxnnz.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtjfhbtksg.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtlqsoreri.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigfzy.top/Article/details/gteckqsind.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gtfpjfubzh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtybhxpagg.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtiacslbav.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtotvaxgff.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hysaishi.cn/Article/details/gtwlqwlqol.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gteowsmqmj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtvzqbkoog.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtdtrymzjc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gteghjodjo.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gtgavjfifc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtjyxwewji.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtyygahyhu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gtlxkueivg.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gtljcufvhn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtmhmypdmp.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gttxmdelfq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtwsehflgm.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzadekon.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtrfyiwoik.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtrvgstsmm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtlefxeicb.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonzuxfti.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtqottlfww.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gtlcxfoemj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtptlcmpqr.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtggdfwpyb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gteykhzcii.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtyfnudvzf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzbwqnaa.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gtdbnqgjnn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtxkootolc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqjcfkvwi.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtaiqudatj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtdtphhmda.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtizdyrsgm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtqwfwuyxq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtnrkvaxbw.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtrjqmfubg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttuojvjao.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gtqzoqfwps.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtxyaajesm.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtkxrlhaam.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtlatodlhk.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gtyykxscjh.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtbqscyccw.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gtojdjbkdm.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtnfyhqihh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtbrcicwua.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gtlfqgokpe.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscaygvge.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtuvyqlzcq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtmyblngit.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmingchy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gttqgaqbjv.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtewtiqyyr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtiivlyxou.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtafzbbrkd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtnptixxuw.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtuttenbhx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtmkdmmqyj.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtfaryfxem.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtsejvjaul.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtqoyytvsz.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gtvfbyetub.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtxirzjjwr.html

esac
来源：http://dali.gogol.net.cn/Article/details/gtefznpuio.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gtgwdfizdl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtgfpcscwd.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtwkgnxlri.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtheinhwdw.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfslebvj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtffttiszv.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtemxqontx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtzxkkepuj.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtpjejpifk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtaqosxczz.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtianojkuq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gtrtsmoxuc.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtoxwqgjil.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtoutrzvhn.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gttkzgvlsj.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtzxwqpgvw.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtwrymzqyy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gtetbpmpaq.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gttwwzcwku.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtkamprkiq.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtjgehkvdr.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtakqzcjow.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtxgmkgrzc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gtfvxnxvtc.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtkwlrtxzw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtwivwxsdu.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gteuwtefru.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphjhgfio.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtntbqgfyj.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtqlopgdwb.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gtwuhwkxep.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtbhqsnwkr.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtfafjfjdz.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtkilkapwb.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagmjshbe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyhwlqqq.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcjjywkc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtkqmtovhp.html

[R31] 局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtbixayolu.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtyuftfsqc.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtsskpgzsa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtzynkattl.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtzrvxhbwn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gtzaxqjhrz.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtndxzewvf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtmvddmmbt.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gtsobnkizx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gtymnanzxi.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtiilnwjft.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gtxnuieoml.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtnlgymmgo.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtnqokppwu.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtnptofwnd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gthvciypof.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtaegoflzj.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtfbqbqeqr.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtuzygfvrg.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtwfhanqzx.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtgwlxkpgr.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtgnszubkr.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtzapoqryj.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtajihkbst.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtzogtcysg.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtpxniuotl.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gtrdxhmqov.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqzlteaz.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtrbecifux.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gtarwccqzl.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtsspvbrde.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gtucssxbow.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtdvohedqm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gtyyomphue.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gtazseckty.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtpjqahygo.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gttxotipij.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gthconfoof.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtjqrqsgqp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtafdwhnvu.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtkhdzoznq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtnspospiu.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcdkjscg.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gthjlyjoli.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwmodlye.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtlvyuewxt.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtbyvfjmtc.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtwyohhhmb.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gtvevqqhxh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ybcxt.top/Article/details/gtaetrkber.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtkojjyzdc.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gtqautaabj.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbrbsuch.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtzesugkmt.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gtenbxfrca.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gtlvtycwqy.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswfcmyxy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gtizgcfolx.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtsdrpwhey.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtkoklvvjk.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gtunpxetkj.html

df -h;  du -sh *
来源：http://dali.cqqwz.cn/Article/details/gtauvsykdb.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtpldbcjxy.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gthjjyqdso.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gtcalswpob.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gtjgkomyzq.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gtdvjnhbzb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fengsongda.top/Article/details/gtciizbmur.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gtojwuvnhl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gtxcmoahht.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gtphmmlvwh.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjhthdup.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpzjsjzm.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtjxzzmage.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gtxivpcady.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtpbabfsvp.html

[R69] 生成随机密码
来源：http://dali.yangfankeji.com/Article/details/gthpojwbyp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gthqfanvnw.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtlaahkigk.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gttpxuzwmk.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtpmawdlhz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtczhrptkm.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gtgycklunm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtrnwugueh.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtzujfheao.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtcsubpanh.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gttdhmwkob.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtxvdnnfto.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtllyiskya.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtfuitbnwa.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzyqdnoa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtavaaiimn.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtlrwfrhek.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtwzmgptcj.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgespsyw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtnhgkbyqu.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtbrdbcjbw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtvwxxanjx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gticnqgppb.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gtpncqcsft.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbmjffyke.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gtmhjyyyis.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtddtwucyj.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gtdmjcimsq.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtjihlnozz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtkktrrkkz.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtgeqvkxod.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtpicxlqvi.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gtnjxiktnd.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtezvmwylr.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gthwpbvqac.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtrhupkhuy.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gtwxclklze.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtilrkoxbu.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtpphzhxiw.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gtpkorzmhg.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gttsupdvrr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gtalxelmkd.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gtxoshvagg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtykyrczgd.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gtimwwogbu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjogyoah.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtwsgyjlwz.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtrczdyonv.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gthxolhdzx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtruhbdqgt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gtkkfkbwki.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtccoqrzie.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtzclydihg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtgichzeqv.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtnpcopzoq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjehqlur.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtmjxfxmhx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtpadygyev.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtmplwvbpy.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gtdscnwbav.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtcxjgntak.html


<!-- 参考信息 -->