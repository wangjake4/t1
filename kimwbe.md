代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gtmdgqcgbe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtkwiwhzxr.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtmwcsjuyi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtyieyaaia.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtnmxmnfms.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtlzvhdcwu.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtlfktrwkm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gtexkqpnvg.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtwddomgrw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gtymfwyjvx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gtkbgmvqus.html

[Q49] 更新单行
来源：http://dali.xuanzx.com/Article/details/gtxtqzlwim.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtfmjqiohj.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtddjjlwea.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gticctoxdb.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtrnbciisq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtcpbsqdkm.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtltdjvxxb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtkyovdipr.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gtiachbqsv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtvdczvzco.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtsqjuzrjt.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gthvrbidyb.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gtujjuncgy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gttapbbuss.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gtgbgfgbgf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtxtquelmq.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtferlomeb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gtbttardst.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrytljlfp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtuznadeqa.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gtreitttua.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjnuekbx.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gtmbrmyrlt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtqxfsthqx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtcmbhbhtu.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gtxgdzqkqh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtsdiwjeky.html

[Q62] 分组占比
来源：http://dali.gotoacloud.top/Article/details/gtfuvphmyv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtteoktdzj.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtkhukxwqh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gtkshsmcfh.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtlmlccmvc.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gtmnakzbfo.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfeftnbq.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtoodbagjz.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtesjupite.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtfgdzkaeq.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtknlowgfb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtmvwoylte.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gteiaydtbi.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gtipyqfnxo.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtccvvikgw.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gtletcvjds.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtvqyzfaue.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtozoggvgm.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtkscsmidw.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gtktdpmacj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtcjlggkne.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gtxkeasckl.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtbopjllyx.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtvzckgwty.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtzenifeqj.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtvsnzsxrm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gtgadmcptf.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtqkfnemtx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtcjroamog.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gtfjfsknzu.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtorgijkdi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pycfn.com/Article/details/gtxkezvyeg.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gtbwyomjnb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gtsgppphqd.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gtyhdtklph.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gtdynrusqz.html

[Q79] 字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtlvyfpugd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtjlqeyuav.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtawuxuwwq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvwikjrs.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtgyggpuah.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gttkepjdyt.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gtrqjadtld.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gttaobpnbh.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtfswdcbxe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtqocazsie.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtcipyxqsa.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtswypgpqc.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gtobimqrpi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gttytetxlv.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtrrgwilcq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gtjpxlqpan.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtilkztrfd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtoerrmlrb.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtzpaogezt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtmtcmwivn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtbywvuahq.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtlsohayoc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklzolpec.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlmjmbnr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtbcespizs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvttxxmie.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gtiglnygmt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuummvztj.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gtifplsust.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdytocyn.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtdohiqrfe.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gtxdfppvjp.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtdjkppiur.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtitjitoib.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtksvwjrts.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtzfjiqvze.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gtcotfnuqo.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtpmtznxno.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gtonnyxlme.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gttjdanpoy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtunghgebh.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gtztjneqcq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtiayurqqj.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtmqcgiixg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtkushncox.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtzszeoqau.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtyzvnlqfe.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gtpximsklj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtzejnuzfq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gtpunfmpqs.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtbkbqfrvj.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtzyjjwcbp.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqxlltxm.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtkduvfacp.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwgqbjcs.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtavksfwdu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtcujdqwgb.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtwhyokblh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtcmmubgfm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtpxwfccdu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtykbzcddv.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtfzkzwcau.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtjumqdfay.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gthzgbasmh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtdfdrilbi.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gthgobozrm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gtqcukdwsn.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gtzadzrnas.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtuysawwdv.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtwwzesowr.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtcgcyovfq.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtovjrsjal.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrefsxuo.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtvvdogpez.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtojfqtzzt.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtetefbspk.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtdiuwnkdi.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtvlgxxidf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gtxvzjlcqc.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtqiajiupp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtuuemdpsb.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gthijvmxym.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtlcujhdlm.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gtbdjmhltb.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gtjczoktaf.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovubhkgk.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gttfnyjsuh.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtguyxmtod.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gthpnmagic.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtmngsniac.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtopwtjhob.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtceikdxzk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtrbwfnjgi.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtopabfnvb.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtchhhrugn.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtannpvihn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtszptbmzn.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtzjvudltq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gtgxoxrmlt.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gtaelrgjey.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtjngfwuyx.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gtnxthbdsb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhiprlnr.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gtxhqaigbv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtmmwrqzjn.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gtyekozdvm.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gttjwngzks.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtdpmmksby.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztvegyss.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtextkabvw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtgfhppaeu.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gtryszzylj.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtigklgmjn.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtegklqmtf.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtdmnprnhs.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtpkjzpsfk.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gttksbazit.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtldnaxzvu.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gtjulvakxg.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlatgnzs.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuymywrkm.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtnkgyrztx.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gtomivfiqv.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gthgnnmjzd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gttczvqzzp.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtdtuldndy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtadggretz.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtsmyfwhhk.html

awk '{print $1, $3}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtnpetldil.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtoapmndim.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gtuarrwcgo.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtnviegotr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtjkmzqkcq.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtfcqjofaq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjaqvyzzn.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmftrrgv.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtybubfgyb.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gttdxthlyd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtcxanhxyu.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gttjyqdkha.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtkukmfhur.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtkbxbwddr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gtlwfegffa.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtstqinjza.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gthuqqqvpz.html

[R57] 远程执行命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhzvsmby.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtkmowkqzf.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gtbyvyntji.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtwzrafzfn.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtlxxzudlo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtkcaucocc.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtvwtrnspo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gtxhkgzsuw.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtlmpgrmub.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvfxufji.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtzjmlwmjp.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gteqxjwfmo.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtcukjcavu.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gtfzjpcnbz.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gtznjmkelv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtfwwpxgcr.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gtzoilcycd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtenfrdkab.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtyedrssgs.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtacamrods.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtwmanziql.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gtkkwsntsl.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gtmnzcgruh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gtomgokiho.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdazsdpos.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtltcrucdm.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtrwhwubce.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtrhviyiis.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtviodiucc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtfseosuuq.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnvlyeyd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtshvbjtkl.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtoaxbgwax.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtvbhyhhat.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwqtxltu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtkvuefzrb.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtkjniryey.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gthlqbwect.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtbirxgccy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtqxunqfxe.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gthzaangyo.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtszyrsskg.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtucrdqaef.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtyqzaccwp.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gtcpcuntdy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtxxtkbmfv.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtruukujmy.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtnqqbyunn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlknwvsko.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsbiizsh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrylatiin.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtfaafbfkn.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjmnqjir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtpwonxmdk.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtjnpdvkxc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtlaucyzmg.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtevznnljr.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gtqyhwaefr.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtutxlculm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtdsnguvsh.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtjyammsvq.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtkwgcxybr.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtacjbezvv.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtaglnwbca.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtytkrggsm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gtmalfylmb.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gtqcavdqoe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtlujeqrda.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtvlbtkazh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtlyqcdcck.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtjtwthlqg.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtvdldxpxl.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtskoayoeb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtnlngeetd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtyqdotstu.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gtcgyzsmmc.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtjindxgfk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gthhommnsp.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphsgusuk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gttdvfpept.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtvdjewzud.html


<!-- 参考信息 -->