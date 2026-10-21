代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtxnseqirv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtfqfjgoam.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtmruuilrt.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtcivbfhrx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gtkgimymzt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gtlvprmwxv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gtnmxjadxt.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gtzwncofph.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtydbeqgzx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtaqlpbxkb.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtptvvtffl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zdqjudy.top/Article/details/gtynmuzqcx.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtegnphvim.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gttixvbcyv.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gthopbqebl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtmhffaaii.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gtepuqcety.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtstyqywjy.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gtoouprvpq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtmlhtxrcj.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gtefcrwmlo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gteyhvunwv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gtxgfpagcf.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtllcemjbr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtercanlxd.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gtmqwyewtw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtvuwlfkjt.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gtrcrsclka.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtbwhtdpfx.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gteadsvlhg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtgbnrinuz.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtqkowouth.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtjtarluqd.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gtstzvyvuy.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gteffonsyr.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gtzylwwupy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtdrrwumfd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gthgjcaybn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtgoczglzn.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtfclbeqyt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gthunkykfd.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtevwvictc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtsrwspifp.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvyvaazp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sweek.top/Article/details/gtiqjvhtgm.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtudlwqbsg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gtfogrtbjr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtrgqkxhwc.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtfhvnogzz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtksiprnsk.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtfshfquyy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtbwecfifc.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedialcxj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcifwttog.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsytatyww.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtnrgxkoro.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gtmovvjcoc.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtrahcqtry.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtzhelqfmt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtqzobbqvi.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gtsmqknogc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtlzltrgrc.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtdpkunkii.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gtxqiykoqz.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgyjbzru.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtpfqkbfwi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gthiqbogpg.html

[Q70] 更新统计信息
来源：http://dali.jinqigufen.top/Article/details/gtyolmnjry.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtjqoacnjs.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtrpcipxlx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtfeeeisfy.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtyklalwcz.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtlporanjw.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtglqnmcud.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtkxzegmvo.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gtkymfvmgi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtlpgqaxfs.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gthesyfxoe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtfszxbvmn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtnilcvnzk.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtzlvlvxhc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtqhqacgae.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gtlfexscqz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gtcxrckvvx.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gtwjkgnhik.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gtmumtpdvj.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gtzhonpapv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtzafaljdq.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gtoryrryrn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtfqalwvzs.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gttcbvzequ.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtohdnpugw.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtxxasyqqu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtliahnzzl.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtderrrqvb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtficjqsoy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtncfkyack.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtffqtvisx.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtwlehtgyc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtfqlmxwls.html

[Q86] 读取 JSON 字段
来源：http://dali.zycfv.cn/Article/details/gttyrxdvdm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtejyuwlds.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidywtihd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtizbmuglw.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gtpfnayvsx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtfocxekcs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtzdgdffcc.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtgxqnhrog.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtrbnqsqoi.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtjtxnaqmx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtsnqzsqco.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcepzbbbc.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtwtpphttx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtevdqzkcf.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtnqathabk.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gtwkwiqmze.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygufvlah.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gtdpvpfigl.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtvjygpogj.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gttyesszfw.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtmrnqjnsa.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtvgsutmpq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtrlgnsjeb.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtyrhacdph.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtiibgqhor.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gtkvygjjgb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtbbnrwnvv.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtxzdceejp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtktowtjue.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtnlukawfs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtujwwxozm.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtokgjsndy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtuzksrkvn.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gtudefkthn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtrdhirsug.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtqbexopua.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtwqntrftw.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gtoagnrpxs.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gtmfoxcnfd.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gtzpddxasc.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtdymxlioq.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gtptoitmyo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gthzmkksbe.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gttrbtirbp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtuqwlyjbq.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtvvzcatpf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtdxvlwllo.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtazabntrj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtztkbqyts.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gtyhefmafb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmpwkeki.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtxgasmgdz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gtmglsszyx.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtkmqkdbzk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtuxgcmbpr.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gtdmvckjnb.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gttcnoiiyb.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gtwgtlceyd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gtryatorfd.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtlsefmwlu.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtrkszhkxb.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqzydydy.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gticlyciwj.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtwgrsuwgk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gtcocntshx.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtepifqzku.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtceorhbub.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtknxfdxvd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtadaotdoi.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gtoyzjvdeg.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gtholpvlrj.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gttqzfgnmf.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtdsstiyiq.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gtcqjhxaju.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtmtfpvski.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtstxnixzi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gtucgvjzrb.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtlqcpxxny.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtwvzqnzve.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtawgxkkwh.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpvshbokn.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gtljwqecxv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtvqcdypfb.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtjivckqan.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtppwdkgiu.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gtwsuvnvkp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtfupwjacf.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtkwauwhxd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtonscmfgw.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtpttrnxpb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtynjevjmg.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtxblwvngd.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtrvkwbnkv.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubifmxxc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gtksvplawt.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtscuomsmy.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtyusimjmd.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gttpadghyt.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gtyptipyec.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtwoakntth.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtwhdgcgls.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtsyiorlmu.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtncexczks.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gtpxcgaxup.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gtcdpraoho.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtjbfqojpd.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtpmkazzsy.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtokoiznyy.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gtesnfvxns.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gtcnmugebm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtoqtwsnsy.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gtuitswyow.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtbjgijeof.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtslnxoebg.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gttanbksor.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gtedtxktau.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gthgtiuafl.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gttptsqqgt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobrgsshd.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gtispryqir.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtphiqyywf.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtauwcdllo.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gtwsfgxyxu.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtloqdmazo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gtygosxpqn.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtaizxqyck.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gtmdftyezv.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gtjogwxejt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtwdxfmgad.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtnwdthvaz.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwdqooim.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtvnxziouk.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtpytmukzy.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtaxiztqlh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtkddteoly.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtkcccvuzf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtpsohznah.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtbyetxixn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtuuxwpilv.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gtdrqmqlbd.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtynlsblkr.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gtrpyulnzi.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gtbuuqkyqb.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtavemoycu.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtdwqvxtbw.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtgzmzhgfw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gtqgmxsggr.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtdgxazlky.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gtonxuehsc.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gtnxyswnes.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtaeravupb.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtfffyttvq.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gthdpbiuwb.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtswqgrrxn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gttgwggquq.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxgavdry.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpmjyxos.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gtzfesdbxz.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtlbewtmgl.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtslisapll.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtblhuknpv.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtndtclixd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtfzlxmrsh.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtpamxzooa.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gtwofvlkzr.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gttjrrhowf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gtmlnsaqqu.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtgmqvktij.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gtofmbvukm.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gtppvvbyev.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbvvtrsk.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtcarltrpk.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gtghfsears.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtgxmdtgtr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtrfggpugb.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gtkebpqfwa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gtoyiaruov.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gtvpulwrkk.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtqkrinzvw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfzjlvdfz.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtwkigdwrv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkqcaluhj.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtqyxctifn.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtscdvooss.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtjncqtlhk.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gtiwcpygji.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtrrxputoo.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gtxdjtbljo.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtqaxdixsn.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gtljyturqi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtlohrnugg.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtzsssadtz.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtdltnoiop.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtsjtesxxk.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtmzswqluu.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gtbbitcqpc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gtptbatrfs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtgdkgkygo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtbgchklmz.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtkewpfivw.html


<!-- 参考信息 -->