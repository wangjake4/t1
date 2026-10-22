代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iiwlfavx.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gt2inekjkuv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2rawtesvj.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gt2muaglvqc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gt2njdiqoyb.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gt2envfopyc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2greozetg.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2wrzlniex.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2mqfbdtim.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gt2yovbgwhp.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gt2glklmpxb.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gt2oafwvyfg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gt2dhlkrmxs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gt2kxvshtmx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gt2vrbdwvnp.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gt2wtqybnvh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2dcrjxfva.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gt2naevmlet.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2foggzcfr.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gt2sdzabvex.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2oorizfgh.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gt2pxirknbx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gt2ybsacxzm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2acwnsjtd.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2diukwlfh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2lpcicwaz.html

[Q62] 分组占比
来源：http://dali.yuxming.cn/Article/details/gt2rhiabkqo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2uvblcqdf.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gt2dgeupqxy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gt2lsrotjsz.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gt2kyfcbxbo.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gt2yhnfames.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gt2uyjwuwzl.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gt2fvbxxqic.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gt2avblcdcf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpqdoaqs.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvpdpdsw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gt2fqqeaols.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjjpfbvc.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2rfvblenq.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2olxwijxf.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gt2ckukmdmj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gt2pecmqrer.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gt2bbdoqywp.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gt2hvaiofvz.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbnckvag.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gt2fkdvrfku.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gt2bqstylxl.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2nfqzeeqe.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gt2wpwzkrae.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2ahwdooid.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2saskjymw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gt2asheiket.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2qgudgqiq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyvjyoht.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bimsrmgp.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gt2tfhwyjcq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gt2fljvhyzi.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gt2rdoritrt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gt2xbcjowmk.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2znjodfke.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gt2qqquqgbc.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gt2wpkqqjoh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gt2rhbfkgtd.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cssqjxhi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2svhortfy.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2iwbyxvgt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqaixfyp.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gt2rfdescdx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2hbbvkldy.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2nlnvflqh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2xrfbhdjw.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gt2rfztxvff.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2fddxinyh.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxzheqrh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcjnwrhv.html

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gt2mzfgdbnx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gt2olxugtzy.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gt2atdswgcm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gt2dbkhjcex.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gt2bcqrscik.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gt2ragzvxwf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2xxhmcftd.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2vgbyxcrx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gt2dnzycnwm.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gt2zycfnhmh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gt2hppbxcli.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zocqamxc.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gt2igcxarzo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2juoyyktz.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2tgfcshea.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gt2lpomwvsk.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gt2bkmlawxy.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gt2qjinbcxj.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2zdkvdrqo.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2zvhgoyeb.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gt2hjhxupcb.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gt2ifzqioim.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gt2ozaotonj.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gt2oewgqprz.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ohbcynqn.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftyfsfos.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gt2jofgorlh.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gt2ahaokslv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvagjvxg.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gt2xesjxivx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2cheberka.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2vsvanhze.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gt2yjlvovmq.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gt2pwqxcmfm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gt2ogvborav.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gt2ocgefzou.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gt2yvsompjl.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gt2swqipsil.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gt2qskmswyo.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttcdzong.html

esac
来源：http://dali.ppjwa.cn/Article/details/gt2pexueuxx.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gt2eyodkqwj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gt2ptasrmwy.html

[R13] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gt2fjwdyhnq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gt2gntwlhkn.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gt2tiujnbbu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2gbgfklmo.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2blwsjsme.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gt2wyofxpkl.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2xinlvnzm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjzfkffj.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gt2lriwbbxc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gt2hwngbidy.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gt2jzzommxc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gt2rvomeaoj.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2crsdldpc.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gt2rqdchgvh.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gt2tegvhaci.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gt2hnkzaagu.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2ddwembec.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cecxrsds.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2vaitaocb.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gt2liilxijd.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2gjwhvaxe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orzdwgfj.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gt2huizxhbg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfnazezo.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gt2ckxqxwap.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gt2hpwtzkbb.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gt2gqoaiuxh.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gt2fjewzheg.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gt2tqbxxlrn.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gt2kgmbuqwr.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gt2bajvqlub.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gt2akqjbbik.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjtylmgd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gt2vggoywne.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gt2clkiufue.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gt2cczljtvc.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2kabgiwkm.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gt2qhdbrgrz.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gt2lemcibbq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2daebuwvp.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gt2rfryzeak.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gt2vupqmfcu.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnghrffu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2xbfmhhcz.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gt2lokicvxc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gt2zbpdknob.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gt2iwjxvqxa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gt2xlqalmtm.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2poxcvfym.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gt2krngxgwj.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gt2dliwrzsv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gt2dqcarxfx.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gt2raitezvb.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2wgyzblip.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gt2ykmmzrsa.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2ywtgyoac.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gt2lrexaisn.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2badcyuhr.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gt2jcerpwuk.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2tklnblhq.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gt2stbdyspa.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gt2nqdbbqer.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gt2ncpybity.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gt2inwngnba.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbifvya.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gt2yfoltkxg.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2sehimvec.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.svipenyu.cn/Article/details/gt2orvxtqyj.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2awofzpih.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2szpkffbs.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqglyoer.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzrdpgwh.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gt2vifoxxwe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gt2ygvcvigl.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gt2zdcclhml.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2wgopipwi.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gt2bjxeskgf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gt2ezjgrfjs.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gt2kwqcziwq.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2idurnzwi.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gt2qdokhodm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gt2nmlzxziu.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gt2vvjcogod.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gt2wqoqcfzb.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gt2eqbbwhou.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifbvgdfe.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2vfclgepu.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpbrhhjs.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gt2rbpcqhxy.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gt2rktoxmjc.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyewcnet.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gt2glrwoisn.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzeojytd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqomdyna.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2nvupmgbi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2gronlfli.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdcvgioo.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyfzgbzj.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gt2lbxwuapa.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gt2oonfuctd.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gt2lizcjgxg.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gt2mzaiyxzb.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gt2pyrgoium.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gt2hcmfzhiy.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gt2ixomtlmv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gt2xorjxeth.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gt2bmrxdsnw.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gt2ymkialuv.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gt2carsuxap.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhgbqeif.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gt2xwdgotah.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2ukduwinv.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugutpbrm.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gt2tydwowgu.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gt2udyeeexi.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gt2tgwksouy.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2oergiqxu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlaowxih.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gt2pqcsimjs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2lzmczitk.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gt2hxbfopai.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gt2hoemhmvc.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gt2ofijpmag.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncwqoyuw.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gt2zsgcpfgy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gt2opqdhdqs.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gt2wubvqnjq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2zybrjiix.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gt2eviuiozn.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gt2syubyxup.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gt2eusadseq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gt2wnjdxzde.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzqbpybu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gt2njgyundz.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gt2xlhktmwo.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkzubsta.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2telvmpik.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gt2whdijvqt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2gxbknwkm.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2xqcdludt.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gt2ovzwjtgo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gt2pkllpjpb.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2hxwylqer.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gt2ydeywdvs.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxxxuuga.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gt2qrmxtpie.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gt2fsydbkmd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2nljmjsvb.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2smxaxkgn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wywaxwsl.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2eadbaevg.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gt2qtpdmdia.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gt2dtmpvqyc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gt2cvosfxfw.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gt2wqjvyutk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gt2gabiovmv.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gt2knxbtdve.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gt2vfeunnil.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmmpxcoo.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gt2eybnblre.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2pxfywxyk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gt2sqmnunfw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gt2pxexpjae.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2pzrpergy.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwtitkax.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gt2jajmzcdw.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2bexrztnw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gt2irdkkzbp.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gt2mqmthlfj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gt2stnjhwzt.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gt2anvlubur.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gt2mppvhlgq.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gt2nzhswjcw.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gt2vkxslfbj.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2csdrofng.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gt2wjzpwdyt.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2icmyzazp.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gt2qiieskqg.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gt2dcjksycv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2shqbohks.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gt2uhvmutdw.html


<!-- 参考信息 -->