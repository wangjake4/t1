代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gt2fxkmndpu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2urkfshkl.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gt2wpynentj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gt2daarteub.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2seanwdve.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gt2ijgeurdv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2qnjsprvt.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdpyrzpl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2uxasnqqn.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gt2fjhflhtl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2xopgitor.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gt2qzytkuix.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gt2xivuyywd.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gt2wiieyelc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gt2aubzvfou.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gt2mtshvfza.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2rycakplu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vouyywhh.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gt2ftwoueiq.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2vkxuqndz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gt2dmoewzgy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gt2nmobaxcr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ieycziwj.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gt2ououcchb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2qajypmwd.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnamyjhf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2wnvxvdjr.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gt2bxgbhqwl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2agiwmzwj.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gt2lwlncmim.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gt2eudpfcsn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2duzfdqco.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gt2rtjxcoch.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2uvfgqkpj.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gt2pidthegi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2maprxpmm.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqnobagn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gt2yuxbahud.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gt2uehfkupb.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzmyvktq.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2wchupnzv.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gt2grrctxwt.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gt2surckebx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gt2bbskgpwa.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huumqmsb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gt2uccxnnmu.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gt2ldtfaver.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2fnsxytmq.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gt2bcujfikj.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgaltven.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gt2vbykhcjh.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aowhutqu.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gt2ifustqqy.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gt2fwqyhzrh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gt2pmuhgnqz.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gt2ypiqqlvf.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2lnyocllq.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gt2qqxgdthc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2ycvyavql.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gt2vqlqrnrl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gt2uqapvule.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohgefozy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2nanyqnqq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtjxtczv.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gt2urdptxlu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gt2piyrovwz.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gt2jottbooa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gt2adeahnsx.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gt2wkrwuwgc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iauruftm.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2ffarwqmb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddbbpkun.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gt2gxoctshd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkfnfrnl.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2fsxwpolf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2biatshnl.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gt2fzqaaubh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydclwjba.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2dawghvpe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2kqmbyeam.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnjtcoxg.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2fminqvro.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qulnkrup.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gt2sorghmbg.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gt2oqtokaif.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gt2giwxelns.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gt2jkncgemw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2euirwsrh.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gt2iernvjsi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gt2xkqxyjio.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2fxisehio.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2abvfrnhc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gt2igwmkwlv.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olrwpsik.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxshwfvj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2yszsyeso.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gt2cxckdgub.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ewqwqpjq.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gt2jyqrzqyx.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gt2yfvfqhba.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gt2dablpxeq.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gt2ysgimywc.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2rmophvax.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gt2uzclgebg.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gt2kgdwytpb.html

[R04] 位置参数
来源：http://dali.yanxiufei.cn/Article/details/gt2hhpjpyux.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gt2oijevvlc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2adkruxet.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gt2vlsvsitd.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gt2axilhsqc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2snlatusm.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gt2ltplrkha.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gt2duwcvrad.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gt2tuauhinb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gt2dakdkmfs.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2iijgnzks.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2ibkpdteq.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2etbydhbi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2vtwunjyk.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gt2ycgxcago.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gt2egtzzilb.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gt2hsfpetcq.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gt2wzjcpfae.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gt2vaccbjmj.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gt2pdyaofle.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gt2rvxtkdmb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gt2feburdmw.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gt2llbvghkn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2xfagbijp.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2tbrvplkw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2asrurcid.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2perhkjuz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2dljejico.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gt2teyibsfm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2wqjkirax.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gt2lgkqcxmz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxkulkpw.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gt2jvohwkoi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gt2mowmbtfn.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gt2xgkxmgsg.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2rhsrntze.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gt2avpqynae.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2goswwhei.html

[R21] 字符串长度
来源：http://dali.sysykeji.top/Article/details/gt2qeavzpyn.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hivkwjme.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2qislyqzf.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gt2exgndvgt.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlbbcoxj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gt2fueezisa.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2rylntbrx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gt2yxswomzw.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gt2dibjwdia.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gt2zaywlrab.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gt2skdawmdm.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gt2nvehrivt.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gt2inyttqxi.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlxgovzd.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gt2aabxjqjq.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gt2wijjexkk.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2alutstvu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gt2mqktaxbr.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gt2jpadqbdc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gt2rzgujbjy.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gt2vtjtlsle.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nttqvlcy.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gt2qiqstbno.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gt2gbzyrqhr.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gt2nzoeztwz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gt2wvsktpiy.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gt2rdakyagw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2wvzkkklg.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gt2uwzmwmbr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gt2wtiuvpqi.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gt2zyvnjjtk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gt2cyvzfnsk.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gt2lkrrwecf.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gt2cdscmkpj.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gt2ldvombxs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2vwxypmop.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2eremzzji.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2dbgvzfwn.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gt2dgascymc.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gt2bhpizsey.html

[R41] 丢弃输出
来源：http://dali.vqdsnc.cn/Article/details/gt2hbzocbwl.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2cfckdutx.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gt2ktzmotgd.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gt2sezoftib.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2zcjmrlhp.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gt2ojimszvl.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gt2mmgegspp.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gt2nsghzrjw.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gt2cucsouwb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcytsny.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gt2fnccqpni.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzjvyqbv.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gt2cahtjqlw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2cewqqpdt.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gt2fzfnjxap.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2xzssqapv.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gt2rkugnsev.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2tolkbgww.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2egguadzn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2rtrsualp.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gt2dhhbmbmi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gt2rcnaxivd.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gt2ywmmgepg.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gt2oqkjuihm.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2djoygtox.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gt2tgljehkv.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2dtpggejm.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gt2ajviqwgp.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gt2sjwtyfhz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gt2sesbjbix.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iladrqzf.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2mggirkms.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gt2jjnuoaqh.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gt2nlmcmmsq.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2gcuijnkk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gt2scapnbze.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2jnihhipx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gt2iugjbrhl.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnrccaak.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhaqpjtr.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gt2szeybhhy.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gt2prmzxhar.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gt2bbtsseuh.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gt2ycqiwgwx.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gt2xypetjbg.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gt2zjcsajta.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2vuuzrfnv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gt2veiargfu.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2irqwssqu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gt2vuhiohqe.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gt2eapwhprd.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gt2nmvxubkh.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gt2wopkcsvr.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gt2etsysqmo.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohaqfmhg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2vqsgtddu.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gt2vlmsctwe.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gt2ghcxebxp.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gt2sfyesxhq.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gt2ofkincph.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2flubjplt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gt2uzpvdtrw.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gt2yajwmpcm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxnbcokr.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gt2dlhlysfs.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gt2prkpxass.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2ocuuxmuj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gt2oyduyvvn.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gt2yzpuedck.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fumgxzzt.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gt2dljfqokg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2wozsxeey.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gt2hqorkdjl.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gt2jvyiczgr.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gt2fwycmtyr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gt2xfnsalty.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gt2uhydojbh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gt2xlobqxjm.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycmpxiwk.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjiaffxb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2gwhtajdo.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnmxffer.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2zewlpbdd.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2lxvnuxcu.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gt2abdlpemf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gt2dhlazjbv.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2zngshfoj.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gt2gclghqyj.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gt2suluwzpe.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zourcurf.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gt2cysifqnd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gt2ijgtnwyy.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjyuarpp.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gt2rvdpyhpj.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gt2hbnsjgci.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gt2tkflthwf.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gt2bgnxnfnj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gt2tlnpuezx.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gt2fizupwws.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gt2fsnbrusa.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gt2bjvijzvv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gt2blbqyxgl.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gt2qdhgiftk.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gt2ebafdwkz.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2dzouhkbs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gt2uuayhxzg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gt2bdwyiyhh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2faurudyo.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2lduufcss.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2edswjczg.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gt2goxwnoba.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2hlfxgzwu.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gt2mjxyhbah.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gt2vqgfmpam.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2btfbnaus.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gt2fthnayls.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gt2fcnyulxy.html


<!-- 参考信息 -->