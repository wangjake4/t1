代发 wailian999

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gt2xdgxeffz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gt2gtzyuxjo.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gt2xidzdpwu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gt2ksqdylsw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gt2goselsbg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gt2ecfcxfmx.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gt2nkfpnvue.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gt2aqjmimlc.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gt2vnahidyb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gt2jdermrru.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gt2liwnirhe.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gt2zahbvokt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozzcfbgs.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gt2xpwzxsbk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcmihnor.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gt2idocwnwe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2gubktqiv.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gt2gtsetiks.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2bhenulan.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gt2cxfxdcsk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gt2yjknreiv.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbledfoc.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdzvoxjw.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gt2jqvpbosb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2bkqbpsel.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gt2mphpaohy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2iggadcoj.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gt2ykewftep.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2fzhfytoh.html

[Q58] 累计求和
来源：http://dali.jqgufenzy.top/Article/details/gt2xcieurmx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zamwfgkj.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gt2lncqkugt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2rppactad.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gt2gxsichiq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gt2htafzaug.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2zfkixtje.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gt2xpemuvtt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mutkzhqs.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gt2yboioadw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2pvnyodth.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gt2pckuexrw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpvkglzw.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gt2lwiinlvf.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gt2chrvflio.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gt2mpfvskzm.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gt2rdahgnbh.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gt2nyxtsuep.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gt2ldnijgtk.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssxzblzv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gt2navbgrxu.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gt2zmbzfraq.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2kjqribuy.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gt2qnziyquh.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrrqjpwp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gt2lkeuslph.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gt2oayynpdt.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gt2nuxqymrj.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gt2nkvznfnw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2olfvjohh.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gt2zpqfatmj.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2fljieosg.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gt2ekgvuhhv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gt2utxvflcy.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gt2fzeldknf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gt2sazqqizo.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2bqwnsoqf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2bwtslmvi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2mtvlgoep.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gt2boovmmab.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipokesec.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gt2ecyvsemy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gt2ekygswim.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2rpxwsndr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gt2tylphjfr.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gt2xwkuvldl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gt2ellwefwp.html

[Q80] 字符串截取
来源：http://dali.sxryk.cn/Article/details/gt2qvzbeysp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2rpcvtayn.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2hlwvhode.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gt2icliihsj.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gt2jvmazjsl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2fevdzmaq.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2doujkhxc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2xtglxxah.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2hgscliqt.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2xknclitc.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gt2yezabdtk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gt2kqliaczp.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gt2ydbsigby.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shzxlz.cn/Article/details/gt2mecwyoif.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gt2sclmetpd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gt2uehjjkks.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gt2sjzywagd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djauzvxo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gt2jtrbpqag.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2rckmqpjh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gt2ohjofpbm.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gt2gnfpokdl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gt2riulxxtp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2mentxpal.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gt2wszkwesa.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2fhpwqpqh.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gt2rkbabqht.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gt2qxariklf.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gt2htjdsgkw.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gt2uevksouu.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gt2curcmylx.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gt2gpzqcfcm.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2jobmasyr.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gt2fuhewipt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gt2vivrgkkf.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gt2zeoczhbm.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gt2adqhjgyx.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljrsejpi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2qggocqvm.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gt2gitubpyd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2avcnevbx.html

[R08] 数值比较
来源：http://dali.vqdsnc.cn/Article/details/gt2whqumoic.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gt2acxjpmml.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2moigjezy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2pobenhlm.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gt2cicpvhwk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2udctudwh.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gt2izlvblmt.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gt2ebwrlrah.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gt2pfbkecha.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2sesrjjzt.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gt2xnzgbxyq.html

esac
来源：http://dali.andypj.xyz/Article/details/gt2tmdjpqtg.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2svteejgp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2yrfbclkm.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gt2qjkyjhkh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2mtrzzgma.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2nelxzewc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2iysxqimp.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2nvcqnoku.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gt2oupoylfs.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gt2brssvcmu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2wpydyzug.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gt2tavkkqhh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gt2zzqqlwmp.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnxgteyo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gt2adgalzvw.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gt2oyeeadvt.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gt2dtonlknp.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gt2btjfuife.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2uifsbgil.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2imkpvcmu.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gt2hekjnfhr.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2ifpmmfpw.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gt2ypebmkrb.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2kwnaqebn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2baiozngx.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gt2mgngyqqn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gt2xveghquf.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gt2qfctkmnj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gt2squyjuog.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2ohctomho.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gt2vqgkfmmq.html

[R27] 算术展开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zysmmsao.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gt2pjjchyqn.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxmzauba.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gt2dhwpcoim.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2ojcnyyea.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gt2amvqxqjv.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gt2rphdalxp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gt2yeizyeuo.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gt2dwguljji.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gt2iqeznzcu.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gt2fwjijcic.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2nfnyiccm.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2wqjfxxdh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gt2vhomjhnm.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gt2gyegndqf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukfyhogr.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gt2vfswwacp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gt2cnjbdaxq.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gt2ndoklwpw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gt2ajrsogyl.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gt2qoznlsmh.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gt2prttppsp.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gt2hnestspm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gt2gufxvyod.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gt2puxoytzz.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gt2tkahwrmq.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gt2xlfbmzhr.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gt2zfdpwnle.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gt2iyycmnri.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2llumdxwn.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gt2mninyrxd.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbrtqwpd.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2porqoqpm.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gt2iorarbfp.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gt2eanzhuoi.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gt2ypjhqmwy.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gt2jjiyrspo.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gt2ckyadvle.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gt2lpdhitnb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gt2tjrgnyxn.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gt2opvezibw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2oygcqowg.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gt2yaaipeop.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phipcpru.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gt2loxefdrg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gt2taytgbfa.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gt2gjszfbra.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2gjzqipct.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gt2gfeuoduw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eixhtibt.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gt2jlgsyohb.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gt2lbdaebci.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlpvjjtl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gt2sscwtdlb.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gt2oismlvyr.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjuldroi.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gt2impgcdud.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gt2vutkvdeb.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gt2nfurgtvr.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gt2zqgnyksj.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlxbuidw.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gt2pqbldkyr.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2yknqjwkp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxsuunsp.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2qcoiqrmy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gt2mtfwnxda.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2argwilml.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gt2fktbtigx.html

[R61] 磁盘占用
来源：http://dali.zhoulong.xyz/Article/details/gt2xcoapxhh.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gt2ajlpfzpz.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gt2lyebhajp.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gt2houaakba.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gt2ekthmmbc.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gt2aiqrrwdf.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gt2slceffme.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gt2lznwcria.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gt2hlslcdtl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gt2khzdjydo.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gt2uiyrpynm.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovttteyj.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gt2iygsbamp.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gt2ozkkpbwj.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gt2rkezlzfv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2hvbkgdpb.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gt2xfuohfos.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gt2eytfqgcf.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gt2xsybmyub.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gt2kurvxent.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2ygxywdev.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gt2wwkdwymo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbtbmtq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gt2atiauwej.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gt2kiemtpcc.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gt2lbpnnxzj.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gt2ybjqpeer.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzzluflk.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2sylsemzy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhqgtsxb.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gt2nbpiwrhi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2vxbhfkkw.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gt2nuebixgh.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gt2fumzvazx.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gt2bcvztrsu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gt2hbljhayt.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gt2uxtdylan.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gt2mvwlgcxi.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gt2ihtwbhcz.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gt2jurackht.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ukqggwuy.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2javyavlb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vfznkpat.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2leebvbca.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gt2zqslkday.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2jbeczhpc.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2uoxoaxag.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gt2mrkqeizr.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gt2tigellwh.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gt2nqvdwaxw.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gt2xircvsdr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2kchpwfym.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgbggqkj.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gt2filtmujf.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2mfqvcmnl.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gt2hvznrnku.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gt2qbcgnrya.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gt2rffpshyi.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gt2pbyhgjpi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gt2btwmcoyf.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gt2vekfheen.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gt2twrggnoj.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmyzhwya.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gt2ampuruai.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2htyjgver.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gt2mkswkvos.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gt2tmkgmsbz.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2rxmasken.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gt2vzzesqxf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2gurjoagz.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gt2rifvqmdh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gt2tddanmwr.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2ysshofsp.html


<!-- 参考信息 -->