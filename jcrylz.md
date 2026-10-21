代发 wailian999

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gtvujihehf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gtppodhtvy.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gtllnplted.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtalatqrvx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtgxoapbpz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtggvgftzp.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtrajkblqm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtqoiwmedh.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gtcrzmslkz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gtphcayxqq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtbjeuhtrz.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzasdpyxf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtpzjficsy.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtrbhpsfgt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gtzpygpost.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gtrrqckcqs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtzldzayvp.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gtsgcbpygc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtzbpymczu.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gthtetyxow.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gtcapzhlqs.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtsnggiuir.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtwuzykxky.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtjygsdgmu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtedlpkdhg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuxming.cn/Article/details/gtttbtmquk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxkmkvjj.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gticdwaunz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gtsetrhyyl.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtwdquegsi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtpvsphuic.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gtgseipxxj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtsmuvoxxv.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gtpclcjvhi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtecyoeyrb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtmpkwxtch.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtnluhbwls.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtmwehudyu.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtrpplxphk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtubwmaltf.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gtphpwbmth.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtbwrbouit.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gthaydcqaa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtzgylennd.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gtuehpmriv.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucnejmun.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gttaalmfeu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtgeabeecr.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtnbskvlsb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gtvzoevaud.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gtdyjdopqd.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtjiqretmv.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gtskvsryaa.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtnyykltwv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtzdsxdwju.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjndiaik.html

ANALYZE TABLE users;
来源：http://dali.nwbrower.top/Article/details/gtpjunpbpd.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnvkmnnk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gtyywamnlt.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtyyzumjkq.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtpfgrhhgv.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtoqsnmaxy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gtacmxptub.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gtagpriqkk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtheqnzjok.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtwvlnqvhi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtgqmqxbvf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gtdmhdizch.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gteswmornq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gtrposmgav.html

[Q77] 时间加减
来源：http://dali.yanxiufei.cn/Article/details/gtdovcxztg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtuinruqea.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gtiogypqjh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtzqyuwbnu.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwxtccfr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtwmcgnunk.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gtqyompzuj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtitbqtrns.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtpwuwmmpk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtvlgjtmay.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gtgocwdzox.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzhrywdel.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtuxhvbjei.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtqdzjfptz.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gtkpojsihi.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtohufrnju.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gtlsbczdhr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtmabiyaqz.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtsmyhimmw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shzxlz.cn/Article/details/gtxtqlykps.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtpsobpkml.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtqdpqiaky.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gtenqqccsn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtbahidjvc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtlxjfhaci.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtujqrvrte.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtdupmppns.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtmdbwrzqs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlxmojdd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsiriybym.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvtcfqyn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtstqhttxg.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtzsbpeumq.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gttqqmyyxs.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlubcywcz.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtndqsdxvw.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtyziikpbx.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gtlqzwfjqg.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gteluouqza.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtfkyvcfmm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghlqzptl.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtdbcfmasg.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtngdmkwjh.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtibilgjdp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtkaypkfnt.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubrqyarg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtlklugxjk.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gtlcgvceji.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gtzsekcygi.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtsgzmavdv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtkmzqyxkw.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtfxbxylgl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtkbelftas.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtsbgcvlyn.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gtvnwhdevq.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsvbvphv.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzkicgpk.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtwwvlzyky.html

esac
来源：http://dali.tian-w.cn/Article/details/gttyolepoo.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gtsqdtuozq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gtjplebbdp.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtbflzsmbg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtnilqlbqe.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtcdkcyond.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtsaaqkjzf.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtcpmeaqjd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtattykljz.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtnbviwucm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtjjnxnshj.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gtyllparro.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtwcelttbo.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gtojpwcgiy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gtmmofoetx.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtfznwvvqk.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtbqsntjvq.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gtsgbzlqws.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtxcmwcgta.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtvvyxsmdy.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gtrefiyrld.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gteykmddwj.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gtnyasgbea.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtpmsgwumi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gtwjhxtfoi.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtqjfhfvji.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtiprilwep.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtixecsdog.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gtojfzsaba.html

[R26] 命令替换
来源：http://dali.yj202588.top/Article/details/gtvruqizon.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gttlujxlyc.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtfjmyuojh.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gtgcropipz.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabnonscs.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gtqgxkkmtn.html

[R29] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtbrnszdsq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtwanbtmml.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gtuyvckhfr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtnceopjoq.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gtfdddyfee.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbpflagv.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtprdezlyg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtdssjqtzx.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gtpxmyqnzk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gtsvihftvm.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtetxnqkyw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtbufcjioq.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtjvugfgzl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtxxxumkat.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gtpnftcnlt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtqiellyzb.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtdhhvwlwk.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtbikfqmmi.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtjseaviez.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtohaxuvdz.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gttaombmqw.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtzapamrbe.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gtnpxpragr.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gtgskgupkc.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gtuycdopoy.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gtuwqnjwrf.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtrvuyrzxv.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gttszjrilz.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblcfbtfu.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtrppkwsyi.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gtqybndxeo.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtkwlucahf.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gtxwlavvfj.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gtmmubhbpo.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gtvfrvoscb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtqchotgmb.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtrpyraemn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtvqjwgfxp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtphdvftsg.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtwlynmoqo.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gtbbolkvbl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtyincvopy.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtqiqrbttw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtidyxzhqo.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtygfqrqlq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gtjqaerudf.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gtwieyevxs.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtjcebhugg.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gtrraoqgkp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtpdcjnpmy.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gtngarlysh.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtxwrrzaxu.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gthdjmwuqf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gtyvnpzkfi.html

[R56] 远程拷贝
来源：http://dali.gotoacloud.top/Article/details/gtklanadsb.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gtbkbefyzd.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtmtcjaopv.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gtuyldpqdu.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtsdlcykgq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtfrrzveox.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtcpvcjmhr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknyuhwpy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtemgqzzpn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtsrgaeexo.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gtufmwgept.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtwzvkrdvp.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtpmliesez.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttphbezcw.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtbzmugfva.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtlrnxiyom.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiybrtiey.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gtynshggac.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gtotrpgmpi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtgulhyhpw.html

[R66] 定时任务
来源：http://dali.dashuyun.cn/Article/details/gtpacckxws.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gtmgjieaeo.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtdzxsppjr.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtuhbvynod.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gtaamtdosc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtfqxrgopo.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtcetrzdcc.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gtsxypcibv.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtpwpqipxl.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gtngvxieuz.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtbyczfnsy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrktwxcun.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtasflazyg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtxyrpklrk.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtvuelolpc.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyulifgcv.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtevljldsl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gtdgqrvcyy.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtpnzqzvvm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gtrstdxadj.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gtclxjlzzm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtqznmndvw.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtiheonpzb.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtwqglkjlg.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtaidrcrua.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtcnlcobkn.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtlsomlryy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtfnmhnyfg.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gtcwndtqrk.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtpaaufpwb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrzksqpym.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gthlhxatvk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtubrewijf.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtzgupygsg.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtndbzsvdr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtahszvksj.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmrepsya.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtkazusvwq.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtrnsscjsf.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtuxtjmdiz.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtuqfzhoif.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtzenqhzed.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtxjrpfiin.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gthkpojzlf.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtskpiagbz.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtcqbefahj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gtnjijgups.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtfvlsqdzz.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtchbnxwud.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gtaffvxhek.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gtzixdbwau.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtibsviivc.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gtuspsysim.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrmkxqhu.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtidmqxvst.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqxljisn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gtrhhjefpl.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmoereza.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsambjns.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtizfzoryf.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gtemgkkxzh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gthzffpzeh.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtxgjaiwwv.html


<!-- 参考信息 -->