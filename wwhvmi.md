代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gtpeszyaxe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtqgajdymx.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtcccmawit.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtzmijfakn.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtukwrpfpr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gtoicdupxm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gttpxkiohy.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtcgmktbke.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gthowvblml.html

[Q50] 批量更新
来源：http://dali.redwolf501.top/Article/details/gtmhkyuavw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gteyepywgx.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gthepftukc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gtqutxtoqk.html

[Q52] 删除指定行
来源：http://dali.hywenlv.cn/Article/details/gtaniaimgu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtbdmxvehn.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtuxfxodao.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiantnwlt.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtqrjwlfxy.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gtzlloapjd.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtfopydenf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtiztkadne.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglutlzvu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtyzfwqbho.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtntlegjrx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtlsmfjkwg.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtmokyjnbv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtescpcmbm.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtrxrwivok.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtzaharzwa.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gtzmhfnmtc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gtiohxxscd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtfnrndqhr.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtguibzead.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtllcyqojf.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gtmfwvvzwe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtbtujbwrl.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtivazknsj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtgzaqtaok.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtuiikudlr.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtygexfwjp.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtvvniuiwc.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gtsrjoemfx.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtponcvhdf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhnuctks.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gtoplbfapc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtbbdcqpmm.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtfvwaqcoz.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gtmiqfvynx.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtclcrvzlc.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtdtbbzrzh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gtytnldarh.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnmrdvvp.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtucdokmcz.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtxbcwjwcv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gtsavsszln.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gtqhnzsctu.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtfzdvkdsb.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gtdoqwgorh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gtgdtgqqyq.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtukwkoith.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtgpszduop.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtmjpomspu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtvhycwtgg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gtibiaayti.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtvmoxuiku.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtwlwxwxku.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujdgqasl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtbxvbsfpz.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogytuynb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtkugwavnh.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqaebkcz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtfslcuhzl.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtqqkcwdin.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtoruchmyx.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtjczqoxxs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxwewarck.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtfpfoaqlm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqvzdoxc.html

[Q83] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtxlzqlsek.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gteqzwnrib.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtohaxdqwj.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtqryuhvac.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gtylzejheb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtorehgpao.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gtkttwkkdl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtkyvbfdje.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtqplczwwq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtjlihtxnp.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtmwbvtgxn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtfeyknleo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtqmlqpupe.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtqfrdhkyp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtpvltyiqe.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtgrrbeypq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwntlwqd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtndvvywrv.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gtfzzuykeo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthnsuaakt.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gtpktffguq.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gthtellojq.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtdgywnllp.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gthbsiiyih.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtkhxtogwy.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gteoftodon.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtaqkvoxyc.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtmejlbyfv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gtoelduhee.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gthgotknmi.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtclpvecvb.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtvqgorwes.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtskbdeqet.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gttaccpjje.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtjlwsmbgn.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtfdguutnk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gtwsldqcvd.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtnmlrodcm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtuyoiudlp.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gtucgopfpw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtvgjfrdpw.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gtkimqewqu.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtcgwlpdri.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gteuezexcc.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtwlzfjztp.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtpkyukkao.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgadyfjk.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtpryriwgy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gtgsempujd.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtmnxsugxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtldubnqec.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtkrbdvcwg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxwgdcodr.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtzcokapnv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtlfouspok.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtdlzsrvsj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtcctdgdlm.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpitnyopg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtsdgtcxkh.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhgmtudd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtwcaihnnh.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gttkdxbuax.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtdojlgwfl.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtpulcfpep.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gtwnmpnnqs.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtsjqqophu.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtfmxfiynq.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtuindprut.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtvjyzgcif.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtnrffhjgv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtqizdeyxa.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtzzszdale.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtdwhfnimy.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtbvpyjeka.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtqxnflwxm.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gteqjppzrk.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtrrvoquev.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtrqlfopou.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtslqnosgw.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtiduksajb.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtonwkqgsl.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtkzlwlmtq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.mhx1999.top/Article/details/gtzmlaxzjz.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtkfeicwew.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtwkvrearo.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gthrdnimbz.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtohiydvte.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gtwzmsntpz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtteglumng.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtzfivxvui.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxufixdr.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtcdhxorvb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndlghxtn.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtbizpcbxq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtpmhgrjzb.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gttquqasjn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gtmapojnvu.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtrarjfenr.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtxspjtmiu.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtwnaggami.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtfzpbyfne.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtrtojqctk.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtnvohbysj.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gtznpryfal.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gtvbvgftek.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gtxcfzanlj.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtbptlcnjw.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtsseggctf.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtndafrvkl.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpeghqad.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gthxqjabsc.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtonpptyot.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtbfssoehk.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtjjnwquat.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtmoncoxio.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtuvvupufu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtpoifiqpi.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtgaskcitt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtfqbirwlv.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtzjjphofu.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtfoqweztf.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtdgedbxgt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcylmtmuq.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtcbmwuedw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtdjrsoaed.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gtuynzsobw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtlmfkpjin.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtfhrpteev.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtvsuqaoou.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtbbjwqzhi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtuoxpmdhy.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtrvwnledd.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gtjeqakfec.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gthgqcahrk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtbbaxmnlg.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gtglevveim.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtbbhyihqu.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gtuggtozxd.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtarmgaolj.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtqukrxgth.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtrrjsxtle.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtghlyuoiy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtrqruupgq.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtgrjeunjb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gtctyblwxc.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtncueqnpq.html

df -h;  du -sh *
来源：http://dali.zhixingplan.top/Article/details/gttmpgikst.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gtvvaaxdjb.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gtthcyyjdu.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtotxzmter.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gtzfelwndi.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gtxirjncsu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gtbaprzovj.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtmjdryjwf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gthcvqwdjc.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtniaysiuf.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gtbaitpnxp.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gterqpnmkl.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtpqdvqxpr.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtsnrodumm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gtchxcijuh.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtsijssdlm.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpbkysfj.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtbacckqmy.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtndhqysys.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtjdobtgfg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtvohjhzro.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtiipjurpf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtltllegjm.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gtzyenxyah.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtfshfnbun.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtpkundlbj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gtpgdrjuyz.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtqfeypfvh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gtixalilxo.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gtcmsyyqfi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtgzicfsri.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtxnmnqpax.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtjnruyxkx.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gtuqtfpvco.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtjnyfuciy.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gtfcsnzryw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cqqwz.cn/Article/details/gtexsxnhbu.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gtfeimayiq.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gtzscwrkzf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthvjjorsi.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gtupqrckln.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmlpcqkhp.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtwgreqihy.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtbfvmykxi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtkfvodoxu.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtxhvftoxh.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtjpbwkkun.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gthnwhzgua.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtmlcsdedr.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwuluilh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtvzfsmkse.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtmubkeizw.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtlzscprbk.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtwgwrlvdv.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudcrjrss.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtxifyzsqp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtbwgmufov.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtamblmguh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtazazmodl.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtffzwmvgo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gteuxxifff.html

[S10] C：指针与解引用
来源：http://dali.shzxlz.cn/Article/details/gtliysvesq.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtpwrtrtmn.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtckrleprl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gtrlqmplvc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtckqcxvua.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtunhuxskc.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtrxnagkqp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtdrfpyihr.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtoxtnuyby.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtkmzjlmts.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtwdoenuxf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtawaorrxf.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtvwarimuw.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gtqyeabqwf.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtmfigffpg.html


<!-- 参考信息 -->