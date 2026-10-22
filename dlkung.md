代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.snrcjt.cn/Article/details/gt2nokjuquj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfkzglri.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gt2bduocrlw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmfzicll.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gt2syconrhu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gt2kwpohndj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gt2eyglbhms.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gt2ndwucjqq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2jqnfmvce.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gt2klxvblhs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2duykqvuv.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gt2etooqdip.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gt2kndtjpxw.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gt2vckrnulv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2oqmmurfv.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gt2btyfmwbv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2pajvnore.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gt2jubemtoz.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gt2vgdtlcdp.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gt2yhfgqiot.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2tsolwcfl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gt2zwlbizsp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bydecndo.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gt2khiyytlu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2nueydeba.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gt2zjygyzpg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2whfyprbx.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gt2mvhvhutx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmslozmf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygwbxwrb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gt2utsauryd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fecswtkx.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gt2walsrtyl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhvuxkyy.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gt2ctuunjmx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2spreydqz.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gt2okrapmpr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gt2qxqddksr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgpduma.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfebcjvk.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gt2upmaadiq.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gt2ivdinrcj.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srqwbzvk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gt2xdgpcdjw.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gt2bgnhgogy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gt2oifvrphj.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gt2rlcgbqeq.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2dpxyknts.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gt2ixkzloxo.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqzjiyah.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gt2kcwkvuoo.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gt2zqqfdufx.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gt2debcnhkx.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gt2wxdehgvf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gt2mpifjiux.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gt2qmnrxioy.html

SHOW INDEX FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2vbfbkynp.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gt2tswjcceh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cheryme.top/Article/details/gt2ecferbiq.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gt2dwdqxuit.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gt2sqkblzzq.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2uwbdtboz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2qteizumb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gt2wlksmjcj.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zohovhzc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gt2cbjgefvb.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gt2rctlwkbk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gt2ufbcdupk.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2janbkkjv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2egoxxash.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gt2molqcngj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gt2rkgfqvaw.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gt2hnhxwcyz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2owzumifp.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2tlnyesvg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2grzjysmy.html

[Q82] 字符长度与字节长度
来源：http://dali.zycfv.cn/Article/details/gt2nnuqclhj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2btokjsqx.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gt2phdeapoz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2btfqzyyq.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gt2ycpfwwwh.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2maeyuwaf.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gt2acizeamq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gt2nbrevzde.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2swwvibpo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gt2meacptkc.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpkwfrtc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gt2iiveivil.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2dskqshny.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gt2tsaxkaag.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2txbqriup.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gt2twhkvytr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gt2kdkhluyj.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gt2mqlzqgqo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gt2smbvines.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2qllckgem.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gt2fkxgibxf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2yyrfjtxt.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gt2nszwaaww.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gt2syjirbyi.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gt2egmlytha.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gt2lmjvgjcj.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2ozgqkjvc.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gt2idvgsqgm.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gt2bzcjrwgm.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gt2sgulmtfy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gt2roynopnl.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gt2nrkvqtbv.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gt2gitbwxwf.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2akgnshcj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vssnnoqp.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjsvyens.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gt2iidcuyoa.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2duqzadyg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2pdddyjri.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2fuisqssj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gt2vpxrxjnh.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2dqjvvjkc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2llbrrurb.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gt2rwfufkis.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gt2vtwnyfub.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2btcesatc.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2tzhualio.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2kdyvzqas.html

esac
来源：http://dali.hywenlv.cn/Article/details/gt2ztcwwsnr.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gt2plbayqul.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gt2yxdpznwc.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gt2nkheofiw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gt2izbacxce.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gt2yhhsvvwi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2zawlckky.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2vhtholea.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gt2ogoudgzu.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gt2waqwuzbi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gt2dcbbhmwp.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gt2isiflnzl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gt2bqglrbax.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gt2ysnwibyi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gt2syevwmqt.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2xmgebiyx.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gt2einbzame.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gt2zulpmmsa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gt2kwiewshh.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2ogymfsta.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gt2wgnnwmxq.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2dohoeovb.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2kpcmrldx.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsldelcx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2flyeoplp.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2whnfzkuc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gt2btitqumk.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gt2cowcyvax.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gt2hgoescyq.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gt2kpjzdggy.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gt2xdmnnhhe.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gt2apgkoxbt.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gt2hqzkodps.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gt2rwppfwak.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gt2qlcjqdau.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gt2snnhhsyi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgzxnga.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfqjrheo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gt2gtqbofca.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2uisqqfeo.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oipzhuqb.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acuoxmsw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tvxfgotw.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gt2aazkzhif.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gt2hpxbctfm.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gt2puevwpve.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gt2gitgjcue.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2rjpfdybf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gt2kmvyloil.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gt2sygpqjtw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gt2tndockoi.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gt2mbwaecph.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gt2tvhuroll.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idruvfff.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gt2wehzpqox.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2kblloxrw.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2evdfggvd.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gt2uhcchtjw.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcqcwyxg.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2kqviyrfj.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2rztyhhyi.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbpuixrx.html

wc -l < a.txt
来源：http://dali.wangdashe.top/Article/details/gt2upmtarhw.html

[R43] 按名字查找文件
来源：http://dali.svipenyu.cn/Article/details/gt2sjsdwpze.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gt2bwhsawdj.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hceoiapn.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2tykskfdo.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gt2ngnxqwco.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmchujge.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gt2rlhwsgks.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gt2mkbmqffn.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2hnifmszh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2lksqkyhw.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gt2gescsrkl.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhnbecrt.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gt2nuehswok.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gt2fcnhanrh.html

[R50] awk 求和
来源：http://dali.aizwys.cn/Article/details/gt2nendyimr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2mchamasy.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gt2ieukubjs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqctgiar.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gt2sqlgqrpq.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fymxjzwd.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gt2ctlrnsfz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gt2tficekzz.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gt2qeohejqj.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2rgpkggfy.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gt2nkbincsr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gt2tqobyusp.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gt2muzwhhbk.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2nriaftlv.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gt2zugwwrko.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gt2eryiephv.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gt2gpheoaxi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gt2nfrfhetc.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2sonjritc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwwgfkoa.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2trttqjou.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gt2mvkwxtwz.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gt2luuhwuop.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gt2bwlnqlwh.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uiwlcfak.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gt2egmqakij.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gt2njifdttp.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gt2ighejiuv.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2ulwlsown.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvlmkkmd.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2nlrcfidt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gt2nyisacmy.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gt2qfzgcygt.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gt2rvvaarmy.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gt2gmqqxody.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gt2atojsszv.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gt2onehmyna.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gt2rsnpkbya.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daldtepk.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2kktmwwaj.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gt2eqyqodyz.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gt2rsljvzbg.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdjjpzvj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gt2msdkezbk.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gt2nkdsvpxh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2hhtembpv.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gt2ichsnhym.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngmavput.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gt2ztlbluqo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gt2mhfuwqho.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2sjchetjv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2xrykjxdx.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltcpybbf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2nyjfilof.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjkwqvka.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrxkggec.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gt2uicogdby.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gt2frzghfak.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gt2vtmqtdub.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2halezloj.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gt2rfktqqro.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gt2xmpeysey.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2anpromyg.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2nrygmsxd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2elxcsvui.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2ahnpvhzc.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gt2xsxaayin.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bilzzqge.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2hzyxdyys.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gt2vvntwvga.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gt2zzkqmxck.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gt2xztotywk.html

[S04] C：字符串复制
来源：http://dali.nanxuanxn.top/Article/details/gt2ggfiumft.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2dmkqnjhw.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gt2tviuhvnf.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gt2npxtlcul.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gt2uneuucmz.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2dtoabpgf.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gt2qzeitqcg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gt2bcfbseyj.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gt2aonpahwa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfchepfz.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gt2epiruyur.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gt2trhloqfu.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gt2kboiaber.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gt2ebmvgtbq.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2zxtfksej.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gt2dgyfbsuu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gt2lghjptvd.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2qyhrlljh.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gt2cyfmgddv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gt2qeekjfxa.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kquasxbm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gt2gykqlfis.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gt2etztzrch.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gt2qdmfpdwy.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2yazoqghk.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gt2llnsuvpo.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gt2kvoytnxj.html


<!-- 参考信息 -->