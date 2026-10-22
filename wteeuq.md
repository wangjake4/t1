代发 wailian999

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gt2sddeecmf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gt2hovvezwj.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qofoydto.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2sffuwdqt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gt2zraofsvx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2cnczqibp.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gt2myjquvyx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gt2fgukeslq.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gt2zjhjfzrs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gt2zkoirofp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gt2qloaqwqv.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gt2mpxxynhm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2yrxxqxbq.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gt2bmmdyrge.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gt2ossejkaa.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gt2xmdjbqyt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gt2malcowpc.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gt2sirwtsst.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2icfbufke.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gt2wnqcjavu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2efpopscc.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gt2wkczbyhy.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gt2mcbmiave.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gt2cwjuxbpv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2iperpqxz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2artwycqm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2nrxmhuuu.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gt2esmumtbu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2bxgeamlw.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gt2oizothrk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2tnmguhuo.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gt2slqigdkb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2dkfonfcc.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gt2wzwcffre.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2yijwwybt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2tuqeksta.html

[Q61] 移动平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvjimjnl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2mmkffash.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gt2cfwpckkw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2otntbctt.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysscjtzg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pengpengdd.cyou/Article/details/gt2msjrzogx.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gt2svhcjuvu.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gt2ubyfivur.html

[Q65] 回滚事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmdziifv.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmumbtue.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gt2ssvrenvp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gt2dhfoloku.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gt2jvsrzsyt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gt2nuophctn.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gt2aokbsrdf.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gt2xbyxpoaq.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gt2jzztarjt.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gt2bsoofukl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gt2dxxcqraz.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gt2cltznagg.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gt2jpjrpfhc.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gt2nzhnfktz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gt2ovnsxhir.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gt2jffntizv.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2hnbbiezx.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gt2irskdvem.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gt2ufdcuwkf.html

[Q74] 强制使用索引
来源：http://dali.vqdsnc.cn/Article/details/gt2qpoxbarv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gt2rmidddti.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2hetssgzv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2yawjcsbo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gt2mrwsleuv.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvproivm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gt2efupromu.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gt2gbzfllzu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gt2wgsmhtip.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwtjmtgo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gt2nlhaukhb.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gt2cmcqkdqu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omrgneyt.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gt2crvluvuw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2wecapzjj.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2gdreebrg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2qzsokinw.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gt2lgawtwty.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ngqbwmaz.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2ewjqqepc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkccvvhk.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gt2zifewpic.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2fjovadaz.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gt2jbtpkura.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gt2bwmuugap.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gt2pieptnsn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2dkrlaqkm.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gt2rnobnayf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kkdxnujs.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2fldebtha.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gt2krgsnthb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2hjjyfxwd.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2ncrfnheb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gt2elfsixnc.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gt2hlizjkdk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gt2mfowjdzd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gmlcdpcc.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gt2chthxqeb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2kormifjm.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gt2zftvedke.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gt2sgahcvdu.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gt2qrkazlbv.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gt2jazixpos.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gt2noqvfstu.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gt2bjtvojdh.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gt2qpjojdxj.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gt2ednvpyjh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvjrsvyq.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gt2uycfttgj.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gt2wllxgyke.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2signycsg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2ksqykcse.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gt2xanstxcc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gt2cejbsfao.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gt2pybowhez.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gt2vicrfurd.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2mbtqfyqh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2koyfwlvv.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gt2ddcmgvpp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2dvtzgyxg.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkfjacge.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gt2yuhiajtl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwmeevs.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gt2kklxabtq.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gt2kjocrdye.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2vkphfasp.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gt2yblaldun.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gt2jztasdzk.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gt2vopcibut.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2gukbofwl.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2weicgmdz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gt2saqkihyi.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2gopbpmou.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2xtkuzqxg.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2asuzznfg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2uzcdfzyp.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gt2crxutste.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gt2rscrwgpp.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gt2yhueiwqm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gt2iitzozzg.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2uzrrfeto.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjbndrow.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2lgpnmrow.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rayqljpz.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2xuhomlde.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gt2ptpcutud.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2eietessc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dldhojfn.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2hhvlleoz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gt2vqppoyzq.html

[R24] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2mfkoqpcl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fuzpuprn.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gt2brbjzxln.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gt2qsuovnhb.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhgebtpi.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gt2xgxsryqq.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gt2qnwgmpqy.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gt2gwhmdrzj.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gt2yrszxtay.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gt2leyxuudq.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gt2cxfernwv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fonpyrit.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2juruhoyg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gt2jrwjvpvu.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxtbeppv.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gt2tjnekoik.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gt2okhnjixg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnanzkcv.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twygqnwq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gt2irolumyh.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gt2awvmzqwl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gt2teqaadld.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gt2ylpzpqsk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gt2kaacygmv.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gt2bwrsjjgm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gt2ufpqugxv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukegwkjq.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gt2tggipyld.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gt2guqidery.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gt2glwmqqsj.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gt2gvclbfvh.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gt2sbqqrjhq.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gt2arslfldd.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gt2vvyksaxs.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcpzurfo.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2cywxioyx.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqtigdmv.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gt2dqymllmg.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2vqkzdonf.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2nxjlnoty.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gt2wvbzbtat.html

find . -mtime -7 -type f
来源：http://dali.fzhhl.top/Article/details/gt2ojjgbdzh.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2kuxblruj.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gt2azvzdazd.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omjjbmzm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gt2wxdfaqha.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gt2sbgdlmdk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2usdoyogu.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2luyxwxje.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gt2hysgdbxp.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gt2idrsvxpv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gt2jofmyhki.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdkohhiw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2fpsrxcio.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gt2rpeoxxtk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsqydyrd.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gt2ejfgsgwe.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2wiauibre.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gt2hgoiendh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gt2trhezsiq.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gt2pzzuzllp.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gt2kvfzyggn.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gt2bhfnnqug.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gt2rulhalcu.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gt2wwydohhy.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2smabhgbx.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gt2xalfwiba.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gt2vweeffcz.html

[R58] 下载文件
来源：http://dali.yuanzhike.top/Article/details/gt2smdzqbyq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvmihjl.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2myhrhodm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gt2jstbgghk.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2kbweryen.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gt2itwqeltx.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gt2bawlugxm.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gt2dxmrvdxv.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbjobvxf.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gt2aujsrewp.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2wylslnia.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gt2ptgmdcrb.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gt2xaidmrum.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gt2nfxsnbzh.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gt2gujormpj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gt2axmlxpxf.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gt2elzudqlq.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzkhgdwo.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gt2hqmpubjw.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gt2sbgmfqnw.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gt2qomyvkoe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztsxkbam.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gt2ujykrcem.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gt2piuzxhmi.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2jicdmnsm.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gt2zojvcaku.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2cvjaslxu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gt2tmiexorv.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2caknmulf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2dluvqbkt.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvdhdjyc.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iipphmem.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gt2xocdzyrm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gt2uvmwcwlf.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gt2ivqhdzkf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gt2mgobmomv.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gt2xckcpcpr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2oryewwda.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gt2zigyvflh.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gt2bdobksif.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfnzqjcz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxmsekjb.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2mvjbxtor.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gt2fanaschv.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gt2jojenaky.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gt2tmhmoqkl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jehqlbpc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlkbewd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfgazxkj.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2ncvbdmdo.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gt2mmprulqs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gt2adjclklo.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2sympodcb.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2mqzjzaln.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gt2ppwndwab.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gt2yvhwmvuu.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhgckfnm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2qtxqgtcw.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqaipgjf.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gt2ayeinohm.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2ceezqljl.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gt2dbblsbnr.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2yeutlang.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gt2qgjbufah.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gt2aipejwcd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gt2iyuebunx.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2xilktwuk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2jychnhsh.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gt2wrqzbbfl.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gt2fnmkxeyr.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2qsacwohw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gt2geiqoxvl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gt2iydpufee.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2woyoqyeo.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gt2odpfomyy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxcvpizz.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuavgqjy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gt2mhagguxu.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2wmolfkcq.html


<!-- 参考信息 -->