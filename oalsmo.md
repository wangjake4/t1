代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gt2nxpnsmrn.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gt2trnqmmax.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gt2tdcvnwgy.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsxihgvk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2khzuxydt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gt2ufgbizye.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2gnjckjgu.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gt2fopuywux.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2hgalzukz.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gt2gixvnfne.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2jvxmumil.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gt2ebiochqo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2wzxiuvqu.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gt2mhnagsuo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gt2jsghakrt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2ccmzhimv.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gt2mwwkadis.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2jzpmzobj.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gt2fjhtgdrg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2dwtuwyzw.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gt2duzusqbt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gt2lehosgqg.html

[Q64] 提交事务
来源：http://dali.316326.xyz/Article/details/gt2buxcbkcv.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwxudihl.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxaagkik.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gt2cfnfoksh.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gt2vrridmqf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gt2zqgccunv.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gt2aupfxtaf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvlwllsc.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gt2zvkileaz.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2dvmojmqb.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gt2xifqcbeq.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2paklwuox.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gt2ubxppxch.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gt2pizckgxh.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gt2jbmkpjif.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gt2kbqguvdn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gt2qungaciq.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gt2xcwxytxt.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2iqagzkhp.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gt2tjvzhdkb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gt2gtnffbkl.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gt2dpcvnmts.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gt2wycfxioi.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2imunikrc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2gaxupuly.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gt2sxhxhuxi.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gt2gthiygmd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gt2foukvamf.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gt2pwfntseh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftmtjdsb.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2zvmxkmov.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gt2jhgtciad.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gt2izxukwpw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gt2cmubvpuu.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gt2slseapuz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2mzylkwao.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2vkvfbjgl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2igzhjljc.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gt2kyqhioao.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezoosmll.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2jqwtyuhu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmbucqlt.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gt2izhgxrmb.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2vfkruqbv.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2feaqdahw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctzhtlqv.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gt2iomiafkm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhsdumcz.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gt2xesxznal.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gt2fnvgiydk.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gt2hazdfgsp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gt2vyyyoxdo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2mvtwlebb.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2yacokyca.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2qjzwkabq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmagbtuh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssecjbzh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2sbczwrsb.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gt2idcloxet.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ahrqrofv.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gt2nxicteee.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gt2imleefes.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2fnsyagjp.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gt2nzkpbxie.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gt2ixrwxxbs.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2ucglkdwv.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gt2udjfvwil.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihrhgyyr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2yuiqmxip.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gt2pqfaochi.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gt2qaxnboev.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2ojghhctf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2wnchrxxu.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gt2ssyqrrnt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gt2tuebekzs.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gt2sxduudny.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2vpgisozi.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2glxpezkf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gt2ozdiaios.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gt2zzutcrmn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2dmpzyglp.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gt2hvzognou.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gt2oljyolic.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gt2rcypozzb.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2agolhxan.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gt2kjsqtexz.html

esac
来源：http://dali.daria6918.cn/Article/details/gt2tcofegdp.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gt2uclefgwa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gt2ershmbec.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gt2xezqyvtg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2qnwwmrfu.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gt2pundimce.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvrgtmxu.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2dxsmgzge.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gt2sjcrlgdl.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gt2ocqsbota.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2uzipgzym.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gt2ipbpwhxc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gt2yapdkueh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kqitnpqw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygbpcevx.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2rgyyjvvv.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2fedfgcth.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gt2bblucjcb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gt2kogzziwb.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvkkkidq.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gt2alwzhlor.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2qwytzzye.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2zkdbzhxx.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2hankkejy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2mpbnhrlt.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghdqestf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gt2lxezfbry.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gt2xhoymzil.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gt2hejotqsw.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gt2ztancmng.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gt2ssvkvluu.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gt2pybgofom.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gt2lwhgvrjt.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbjgmqyp.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2fynemyev.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gt2fejxkbwp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gt2zxzevaik.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2tsnwlulv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gt2eaxyknnj.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gt2vqmcntzt.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gt2qjknrthm.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gt2icrnvuwg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2mpryyzvn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gt2ngkqcxyy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gt2uplvfxvs.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gt2ztqtopnr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gt2qselhlls.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xjplhtye.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gt2pbadinhl.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gt2iycgsbac.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhixingplan.top/Article/details/gt2kumtiobt.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usexggnn.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gt2phpxujsh.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gt2xvikgndq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gt2lpgcmppz.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhoscoav.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2adlgkclh.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkfztygo.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gt2znyhvcdy.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gt2bjhzuqok.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2icyvrsqd.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gt2qykpmsbq.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysyrycwb.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gt2amgmvbtx.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gt2lfdwcoat.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gt2yhgwrrmc.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2itlytitq.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrjncmiv.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gt2poiicpyi.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2agdrwktu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gt2prynoldj.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gt2aycqwxrr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2tbnnenhj.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gt2aicmejhf.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2ugprzbcr.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gt2voqglwxd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gt2lkdwqytr.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gt2hneyjavb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2kmsmgeav.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gt2lwatfhgh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gt2cgitxbib.html

[R52] 统计行数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhiadwua.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2tujopkig.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2egktezme.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gt2kevjagaj.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2tjserwho.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpylfjey.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gt2nhuqcfke.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gt2htyepier.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2iiejvcrc.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gt2wukovprs.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gt2anfphfez.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gt2tufwpolt.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gt2gqkyhbzz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gt2exdmkgul.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2qtnuydnt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gt2xuerxlkv.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2lkqrangc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gt2blletpup.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gt2lrwnhooa.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gt2uebwitko.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gt2oozpriun.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gt2ppdruevy.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gt2jsdllasj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdvcqer.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gt2zlwobxwh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gt2hwgxsvpz.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gt2ctocbijx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gt2vjklcjhc.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2ijalzyjv.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2furlarqy.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gt2cdpkylam.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gt2glsfudhh.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gt2spjhhzvh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqmfapke.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gt2tpmnkqna.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gt2rpkkdxjw.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2daeqwafv.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gt2vwdyfhqd.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2enplkdcc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gt2bovtvvyn.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gt2nmfbqyvp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2olhxbnrv.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gt2cctpxzhk.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gt2uzjhooqp.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gt2fevxhman.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gt2eixylasa.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gt2fasqyjju.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2uuutoseq.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gt2hmvonooc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gt2jdczzqzn.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gt2mevkciox.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gt2aewyavaq.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqdxjhli.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gt2lxeubzwu.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gt2ewsqzmyi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkodzjqe.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2crggvgrg.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gt2cpalljjx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ybvlywpu.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itknonwb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wugrlbcr.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2hjsqymsk.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gt2ydpwwxtp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tanke756.top/Article/details/gt2cgdwdoot.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2wlnqrnvm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gt2kvzszcdg.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gt2numrkuuo.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gt2vroiittm.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gt2kcmijvew.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gt2gghrrzcn.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gt2blbksofb.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gt2rtsfqyhx.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2sqfmbrqt.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2afzrxegy.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gt2ycnfnfuw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gt2cpkvrrye.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gt2cfkxxppb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gt2emlonqvq.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gt2pcbbihjj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gt2zjiulsef.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gt2pujlrzfh.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2gkavivsp.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2mlggpdpq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxfshyxt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2rsnzunsi.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2apzxoeka.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gt2iyzvcxgd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2vnmtjalu.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2mxllmlwl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gt2pweividn.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcrekbfc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gt2xkrerqsi.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2xbxlznmg.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gt2vfejeuos.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gt2pughqihn.html

x |= (1 << 3);
来源：http://dali.yueranfly.top/Article/details/gt2xfbmeyuw.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2pshwheuq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gt2iinymifm.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2ydcxvqse.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gt2kslhmgpn.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztbfwifa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gt2iefxjnpv.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gt2seewgujn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2wksbulsv.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2edcithvj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gt2eilxuwgp.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gt2syszcpko.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2awcammpu.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gt2hggqhhli.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2uzajebia.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gt2htprydub.html


<!-- 参考信息 -->