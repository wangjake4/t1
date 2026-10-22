代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gt2buvwatvd.html

[Q50] 批量更新
来源：http://dali.tianlin.xyz/Article/details/gt2izouqzhd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2xlakchbo.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsjkwfyq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2xqcfmnfh.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gt2fmefhnhs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2rjgssdxi.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gt2gbuonrhl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zdqjudy.top/Article/details/gt2hexzvqzm.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pafqspui.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gt2zzfbjkly.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2npxbkbya.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2bbbteqag.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2ctrowgxy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2xkstcgly.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gt2nxqpqrib.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2mgosiyds.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gt2qyavoscm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2knqclnaq.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gt2nwquoyiw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2vyttxzvv.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gt2edytjcyx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zycfv.cn/Article/details/gt2zjuudtcb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2pordawuz.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gt2ckehttoe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2fshneuze.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gt2fhnbfvcx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2migcljqe.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxgxyhjm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gt2ajvbidzx.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gt2orfdwzij.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gt2ndkuhndi.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gt2kxkvbtch.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gt2upccptny.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gt2weorbqgb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gt2noikhxri.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gt2cuviwdcz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2xzbccxvf.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gt2zydngnwj.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gt2sjzkcjyv.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2wlymlpku.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gt2uagiuprz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gt2eltxvjku.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gt2smdcqxcc.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2rlbkcume.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gt2ppybgujx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gt2lqbauwtt.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gt2cfcjvebc.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2yvhijsng.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gt2kkzeprob.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2hhqltwch.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gt2exazwdvh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gt2fzqvuvze.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2crdbwkvu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2orxfsnva.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gt2lewhglgu.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtiivhue.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gt2olvipjcm.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gt2iounfbdv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gt2khetpebv.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxbqhxns.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gt2zhtggvle.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2ayupuiuo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gt2mkfyvech.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swcnvcne.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zanhzhew.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2vnpnonxv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gt2nxzmigbr.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gt2zywkjhab.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2yxlvnscb.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2xixgzxfw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2riwbvjpt.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gt2zsueyxxr.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2xvwvkqjj.html

[Q85] 数值取整
来源：http://dali.xziqi.cn/Article/details/gt2noawckch.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2tfgxwvub.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gt2gnbfcrwi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntyplysp.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gt2qivyqrff.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gt2bcsfbuhm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gt2myrsvvwx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gt2rotcxlzc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2konzxblj.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2mxglfbqz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gt2uswredep.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gt2edbwsgro.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gt2shquiujr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2khpfithf.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gt2lhugblda.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xxunrdzr.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gt2fvhajtfh.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gt2sohtwiuc.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gt2pzuuacmm.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awgvfscx.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2owqycsmr.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gt2kohzpeyi.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gt2qimdbagd.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gt2mclczcdd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gt2hjbjxzer.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2rkhizpmb.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gt2gnwmtzjs.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gt2wimoglew.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gt2exolsqag.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gt2vdgenqgu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gt2jgshhmlk.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2qssmyare.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkfdbbii.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wujouaqw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gt2gejnolxi.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnymeekj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2jgmigdus.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gt2znpekwnn.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2ehtlefcz.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2mzbxjitg.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2prqdlgtz.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2ogvrwozv.html

esac
来源：http://dali.cashguo.top/Article/details/gt2pbaklrtj.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gt2tokbawaa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gt2vjpsyxpn.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gt2riliqlxv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2bvbgbaro.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gt2hgvhlnpn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2bqfvvlml.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2ghigxxnx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2ytgumsbq.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gt2lskodcqi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2lxgjyhuj.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gt2owfdvvzm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2hayywyoa.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gt2uxotrnfg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxaybbmw.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2lklekypp.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2utxslwlj.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gt2zlqwizjx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2ybeliinv.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2xhwfnuel.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gt2tjjpqrvw.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2iadadvar.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gt2dtyjyopa.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2jnhalxyj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gt2sjuwyawe.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2uanapwbl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gt2xetpomqf.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gt2kqsejhmf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqxqprjd.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gt2ssjbviox.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2xighknye.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gt2hraktuzc.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gt2gnuhrivc.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2lolxcxnl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eycitxab.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gt2qlaiiocy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gt2lhyjiuac.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gt2wdpgemrp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gt2yjjltpxn.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gt2rpdqakpd.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gt2btcfdefg.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2qdqecgxc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2hzakholm.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2ibqltyav.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gt2omjrxazs.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2iekofybt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2paglbwia.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gt2rkdmiedc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jyoumei.cn/Article/details/gt2fyqvghmj.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2hzhosnsr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gt2trzxmnvr.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gt2avnoyyvm.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gt2rshtygzz.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gt2csbixjap.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gt2mexmdiwf.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gt2bngpjztb.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gt2kzjpcvza.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gt2jwzbjdub.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gt2whxuilum.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gt2utphskxe.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2pymohzmy.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2fulzwgnn.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdlkcqgt.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gt2znrumftz.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gt2yvtossfp.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gt2ezftslyb.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gt2fhyzhokp.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccwapkml.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqrnxpcf.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gt2dleqxicw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gt2sikpqzsd.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gt2qvjgsooc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2lpfukeud.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmxxoach.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2wopbpoix.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2agswzuxz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gt2bgxudvuj.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gt2tkrscvtl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2eeoxwuwf.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqrrhwuv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gt2hwoeesjc.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gt2utkaotkk.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2zkytjplm.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gt2oejmblsm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gt2xydxcewt.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gt2qbzcklxv.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gt2cppjemoe.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gt2gxeeyzao.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gt2jkypshpu.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gt2xajxztfg.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gt2dbxfzexi.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gt2xlitjvdx.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gt2vsionjzk.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gt2dzvcbmht.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gt2bvxlclss.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2qgaqnhfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gt2sarbewyt.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gt2zcvxguzr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2bndohgvd.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gt2ykdbaglu.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gt2jzetlxed.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gt2gfmpyqek.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gt2sdzdmsjd.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymbnnnkc.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gt2ovrnvafu.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gt2ddnozbyj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gt2otnhsxcm.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2eujzmkki.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2wlmveykz.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmznxlvt.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gt2vxgedvpu.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gt2xklqjjoa.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gt2yusmvpdr.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gt2bmtdsjyu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggfrclqw.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2pomdbnjn.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gt2snjgztll.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gt2mpnyyaog.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2cnewcjvl.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2whsrxgmn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gt2xayvteha.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2kqytydsd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2zpneqxps.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gt2ofomhdrc.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gt2lwnxwhzn.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gt2pjvtdujf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gt2hngqthgu.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gt2gkfshltt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gt2xfcmaxda.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2mkjuckak.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gt2nuwyxhqp.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gt2jfevqwyz.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gt2odfikvvo.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bawjfjkj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gt2jmwydwjy.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gt2isvtpnra.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2ltaulbwx.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gt2begahnzp.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gt2lhliiqfr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwsxhhvp.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gt2yircfwyu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2peswysti.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2rudrveny.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gt2kdkcbzxh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2qybjnnjh.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2duztntfi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzncnvkq.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gt2nrxqztup.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gt2olfbinsk.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gt2jncsjbby.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2bgytjszm.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2asfqjwbi.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gt2qucedwmx.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2hbyzvzga.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gt2skbrojkl.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alkqakkt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gt2icijvynp.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gt2amgydcco.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gt2atucziwy.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gt2ajktdgzx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gt2qnpjblnh.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gt2dgjmlxzn.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2galcudzc.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gt2jxkujkjx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gt2tenwvxjs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gt2jaflyuwt.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2qefashat.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2lmrmubjy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gt2jzjuqrgo.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gt2ugslzpvq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gt2isrgbtqw.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkotduss.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mejtwfkp.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2oskqdfya.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gt2nnvcfejo.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gt2aniwpeku.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elncolzm.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2rnzcjjfj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gt2aetvstgd.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilmrlwwt.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gt2vyvwnagf.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyjikkzl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gt2bnynazmi.html

[S20] C：二分查找
来源：http://dali.zhengqikj.top/Article/details/gt2mbgxqspe.html


<!-- 参考信息 -->