代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gt2ccnvcwqj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gt2xylygtch.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gt2rnxaptop.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gt2ddjbktno.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2cfhxbzdu.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gt2ptxyzkbr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gt2emyxueqn.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gt2xkogimya.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gt2tkgzwoub.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gt2zxbdbanv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2rtkuutxt.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndrespdw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2mbdgolbk.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gt2scfrsdyg.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gt2puvazlhl.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gt2ubdrnzhe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2sfuhxjbk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gt2sjjxxxqw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gt2rvdngvkv.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gt2oxteozqv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2fdzwlfab.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gt2htlzpwfb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2idzsgkjx.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gt2ddbfswcr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2zszdlpqa.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gt2gllxpcvi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gt2wadytkfi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2mdvxuzrj.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gt2pttcheub.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2jnrixsjp.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gt2yycbkwrc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gt2zcuggdzx.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gt2iawcbkxz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258.top/Article/details/gt2tzsitybn.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gt2jzcurtvo.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gt2vjbshout.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gt2lofnbqbf.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gt2cabbymjh.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gt2zornmfmd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gt2kgkuuqtk.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzzbkvbs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gt2qxfagepf.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gt2juqbjrav.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gt2myomaqua.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gt2twsuhtze.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gt2kzsofzzb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gt2lwkjxzrq.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gt2srguyomu.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gt2virypgzv.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gt2tauzmjcd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gt2klakxgdf.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsazzmzp.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2aavubvze.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gt2knmqkfjk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2rqjmvpwq.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gt2rxwvwpnq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gt2evfhkvwj.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2rycuynmi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2nyuzdykq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gt2oawwvtlt.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gt2djtsffub.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gt2pwcbweaf.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gt2thbgeinl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gt2qrjtxupf.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2symdfomp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gt2uotpewrf.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2cpqviuux.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gt2eonenmpd.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gt2uezeuomt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2jbetmkry.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2zenpmann.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gt2ooksezsz.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gt2sfcartqi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2uocpjlea.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2iulakwvl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2uytysmwq.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gt2wdtsexjw.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2sltritji.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gt2qsjdwdef.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gt2xzbjhqsr.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gt2zxhsraqp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gt2dnanrqsq.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gt2uuxdubzd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gt2qijcxupn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gt2gfebqtsl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gt2jjfndykz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2iazxkioi.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2lmbartnw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnntshza.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gt2jhlfjsxa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gt2okqetcgm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ryesjcsj.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gt2nmecugru.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2veclptgi.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gt2jjprctgc.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gt2uzhqaqsu.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gt2nutsbtyp.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gt2eutywjag.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gt2ayctvvqr.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjdezgcb.html

readonly PI=3.14
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tuiyvoyi.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gt2pttkzpox.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gt2tgacwubx.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gt2mbvkbfzk.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gt2uzlamsjh.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gt2behzqdxu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2osglxbjw.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gt2vezjsogq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcxpfhwc.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gt2yumrovcp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2brbsztoa.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2jgqzrbfx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gt2csdfawim.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gt2ymghgoeb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gt2osjqjrzo.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gt2typnfvwl.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gt2bzovqahu.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2kyrgnhwy.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2wnjtodsa.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2bogvgmaf.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gt2jesznsns.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gt2opfzaqeh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gt2dclaqlbj.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2czebdxvn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2gxcxcfci.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gt2qymfemim.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gt2ymtkibhx.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2mdnqodza.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gt2pnjmynxm.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gt2wykykosm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brkjopvl.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gt2qjtuwcrj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gt2klmewegu.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gt2onprmumr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2ozmcfjyo.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zszfjegu.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gt2gbwlcsms.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gt2rrsicixw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gt2glrvgosx.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gt2dzzmsvdt.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gt2nhcrzlkq.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gt2idaucgyi.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gt2raaaxbkc.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2gwqtcsfz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2ojqjfijm.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2rketwbuy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2njywpyer.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gt2uxpyoljo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gt2wmvkumxm.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gt2dxvhshgv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgzavamx.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gt2fukmdynn.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gt2ukmysmcg.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gt2nkzloefs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbwokdtk.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2bkmytvup.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gt2sgppvwtq.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gt2vfguonyq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gt2ekcpweeg.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2lddzcafc.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqvvpbuh.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gt2afnlhouu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymlsiwtc.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gt2tbyzeals.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2zzsondum.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gt2flhzdudt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2thjdwbha.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gt2hqaufgka.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gt2eplfetjd.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgqjercb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gt2ylhvwotu.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpzkonzy.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gt2eebtsulh.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gt2zbzonmst.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2djwswqxt.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2tetytgsw.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2ffpczrmq.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gt2emjewfmd.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcxxudfm.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2pxixfbwn.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gt2ganoqwci.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gt2kvwamesu.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gt2jryidubi.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltuszijq.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxhnreia.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gt2tjtcwhvp.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gt2gwnjwejd.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2bbwyjlvm.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdovsqhy.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhavpjnm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gt2hzkgsqwn.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gt2pszxqpta.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gt2yfuqrbbf.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gt2eumvjzru.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gt2nnrynsrk.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gt2bqxfypmh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2ffpublaf.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gt2lzocbgha.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxmbbenz.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gt2xfvpzerq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gt2jvtlnjlo.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gt2ninedjfb.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gt2eldssoec.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gt2gzjsclro.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gt2bxtvkwyd.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2iqyjbabs.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gt2uvtprahs.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gt2mcmykday.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gt2ephqcbli.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbhzoooi.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gt2gxwpkjhh.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gt2zyozogbr.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gt2pgvogsgu.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2xqtsapcc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2xtvlvoad.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2uzhdbowq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gt2abspqctt.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2oyeuutkg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gt2xckxkxnn.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gt2xdxcwxnv.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gt2wxmvrynh.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gt2cibaydvx.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gt2wtjogogw.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2betkohvj.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gt2wvqqemgp.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gt2heaudarg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gt2lyrmffey.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gt2ztdoalmt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gt2qaahespj.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvawlkxy.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gt2xtpcevve.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gt2azspiegl.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gt2jehijugt.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gt2edfdqasu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2umlylirs.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gt2jcvmycpo.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gt2gldscaiw.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gt2likrnylg.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gt2zczefbgr.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2qnhhqqju.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydveliml.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gt2ucnxmzcc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gt2lmokxxkq.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gt2ldudaerh.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gt2ypdzeukv.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gt2ommrkjza.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gt2wnlxklyc.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2jkjgpegv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gt2imarozfr.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gt2bzwjpglj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gt2yqdhnwta.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gt2cimdoqja.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gt2ccocfqmw.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gt2semjjhtz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gt2kibanrko.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gt2xwsgwheg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gt2licpzrae.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gt2onflzhug.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gt2wfgazvqk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2fjyvnajs.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gt2abomoopj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2icdcplbn.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2oniflzbk.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzwvetme.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gt2aemwnfyp.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gt2erituasj.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gt2pyicxobe.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyvjabnx.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gt2hvadnpyk.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gt2clwpfhhy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gt2yopxgreq.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2wymrsmgy.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxtfiayy.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2izxnumnp.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hebjlapw.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gt2cyqoyknv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2lfczaelq.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbshtsqf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gt2upanbebr.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gt2uwazwdip.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gt2lvwvzskz.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gt2pmqnddyb.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gt2meebnycb.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2jvjbdslc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gt2yfqbjvxa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2jvitmzkj.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2wyedggvm.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxmmqlfu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2mmmiyokw.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gt2ygjhtysw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2jsuvcjst.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2vphmaqof.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gt2agcgkaqj.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2rxutjvuh.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gt2uvgbzyic.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gt2fuayrpno.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gt2jtkvcyah.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2mkhizgyf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gt2qpxsibzi.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gt2mlcgcfih.html


<!-- 参考信息 -->