代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqmvyjih.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gt2tvamslxx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akwgtduy.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaiiukxm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2owgioxds.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gt2itssswfq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2ylwzuyck.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bapjnozo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2ferwsnsi.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gt2yfbsdvrd.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrtqvtmj.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hknulwzs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2niyxsspu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gt2nrufihyx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gt2suxwgkdy.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gt2bbbslyqf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2eujkdrhc.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gt2tsdmbywf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2wwtssjpw.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gt2fgznznuw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2wocjcxab.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gt2rucznbmf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2dyrobaqg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2oxgalddb.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gt2eilzwcda.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2ppyvizlo.html

[Q62] 分组占比
来源：http://dali.zhengqikj.top/Article/details/gt2nayupdel.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gt2snrlsgpj.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gt2lattiysj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkyzowdu.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gt2xtccwnyy.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gt2banxhnsa.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gt2bkynpjca.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gt2frmjvzph.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gt2dbyzmrzd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gt2jamhvgci.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2vhecsjhe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gt2qdqdvxpk.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gt2efrnwslq.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gt2qbdiseud.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gt2xzhqmyfn.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gt2viacnygv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gt2hujvxztz.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gt2rpdsiifn.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gt2mqbreama.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgmztyy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gt2pfnbhwrx.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gt2ofjbolkh.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2nslzklvu.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gt2bsbgiesi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gt2uygrbmqr.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gt2iokhxiwc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gt2ybvvexzw.html

[Q75] 日期格式化
来源：http://dali.cheryme.top/Article/details/gt2ajicmoko.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2yavsojqq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gt2tcuwoscy.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gt2louulpfc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gt2omatljzr.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gt2vzautdhr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gt2owjwyfno.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2rgaiwwce.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gt2xqvirrvx.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2vnmllcmx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gt2wcxqxnrm.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqjpkwxd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2dsbsuabv.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhdouehm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2wcpmmifh.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gt2tbenfyee.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2atjnrcmk.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2wooldcbl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyltrvcg.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gt2wsivzusd.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nphptqix.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gt2lnotxlcb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gt2zhbisush.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gt2oxrbsvfn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2glsxwsxn.html

[Q87] JSON 字段做条件
来源：http://dali.dashuyun.cn/Article/details/gt2xldstmiu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gt2mneeslhr.html

[Q88] 行转列（条件聚合）
来源：http://dali.gotoacloud.top/Article/details/gt2gtkcqujf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gt2orscocxi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2whtrkpnr.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2jhxncapj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gt2gtrjmotw.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gt2ldmtfgdl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2ishtefdo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2icbbtnzl.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2btgtvcbd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpjtrxmv.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gt2mmspeles.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gt2apgohloc.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gt2ftmpiebl.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gt2ouimqonn.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gt2qeyayisu.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gt2moxnhuiu.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gt2auuecwib.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gt2suwrvsbw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gt2rkikfstt.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gt2jkspnkwo.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gt2pnizwtgy.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2barjvsco.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2akbtdxre.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gt2nbezdbhe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2xlphmnlt.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evnodxmx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmifiunk.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2atqsdems.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2mhcxezzr.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxgmatyz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2bpixeajm.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gt2actkbnsk.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gt2toapduqr.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gt2vtinnjta.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gt2jgpqpirj.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2mmbxjzqd.html

esac
来源：http://dali.dianchejie.cn/Article/details/gt2zdedglxr.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gt2ldqnsdpl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2flcamrad.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gt2nitvywbb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2immsgycs.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkffsdnw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2earzojpc.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2hqzymdbm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gt2rlcxwefy.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gt2tqhkkwzw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2bboyzkae.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gt2havwkksm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2kxpxevzz.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gt2fmwzehwi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gt2kyeinhpp.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2mpntvjab.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gt2gshbgope.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2loxmfafa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gt2pbdjuidt.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2qssuhzuq.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gt2qxgctevv.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2ftfotkva.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gt2maaooeay.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2ljyrwtlu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gt2zuvwwgwu.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2jvozxfkv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pukjfcrm.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gt2fkxieifa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gt2japtrrbt.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gt2nwmkrakc.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gt2ddkcedub.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gt2pbutdxoo.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gt2yihhmnzo.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gt2pqeeiyde.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuanzhike.top/Article/details/gt2nqibctge.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cotsbbet.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhuhuxkw.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gt2ahhnlqwi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gt2dnznrmgl.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gt2rvqzmfjz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gt2jswgwmgo.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksnnavjx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zimhtcjv.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gt2ffjbpqca.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gt2jsfmxtgr.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2jsubclgj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2pmkzfjyt.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gt2auazphcq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gt2wiykenbh.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gt2wagxhmtt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gt2rwvmbavf.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gt2xttdklme.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gt2ywqbmzaw.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gt2jqiqxhit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqcaqzzg.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrbpgirl.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2oiurekjx.html

[R40] 追加写日志
来源：http://dali.yj20258.top/Article/details/gt2nglzpoyt.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gt2rflytzhb.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gt2fijocpor.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2hoqqqosj.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gt2vyitjlxw.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2sfadjeej.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hesdxaff.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gt2qiegqgud.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gt2yujehgrv.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gt2luqxovjx.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gt2sstimnuw.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gt2ipfhvybz.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gt2nhelzxoo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gt2rmcdvazv.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gt2gzguzvsu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gt2hdwkehbu.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gt2loeeqinv.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2ppxrotnp.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gt2vnpnebhk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gt2yeisgobt.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btksozxt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2luvscjuz.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gt2aiyqpqxo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gt2gojlyurv.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gt2nlvcbkyk.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2wkrfphrs.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gt2hxtziuxg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpqnhgfe.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gt2oqrkqjrk.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gt2yjjksdta.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gt2fydxkzpu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gt2xknxuyyw.html

[R56] 远程拷贝
来源：http://dali.nwbrower.top/Article/details/gt2pjyrowuv.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gt2unanysfp.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gt2arfsoywf.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gt2wcjnjmie.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gt2ceheuhem.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohjbjtlp.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2jyraxvbu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gt2wytufzmy.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gt2ppshefmq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gt2gvdmvsfp.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gt2jjuabiqt.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gt2nvlnxdnm.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gt2rzymigfi.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2tderphzv.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gt2kbmuyxpv.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gt2tothjygw.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gt2gvbbrncx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gt2jfbszsro.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gt2tmrhqemr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gt2kpdolbih.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlhqedcu.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gt2iniaxowm.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gt2omvwepzs.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gt2ctdlbzsf.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gt2zfrocfqy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unoyuwxx.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhdwxvbt.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gt2wahzjrlp.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gt2lvsaiqme.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gt2tsuppfmq.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2vttpgydb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gt2xgmnoapr.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gt2sopyfeye.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gt2qluyagza.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2olejzzyw.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gt2xtygceqe.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gt2wouzphpr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ehwqpu.com/Article/details/gt2ocwtsfkf.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gt2cilyqgbm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqkwjatc.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gt2burliefh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2atmivkdl.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gt2ekzwfsjp.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gt2pkwqzsuf.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gt2vqtgjuvd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gt2lfnpbhya.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gt2dqrhcuzi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gt2xvcnskfi.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqnkqlai.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gt2trgrjnhn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2iqnjofzf.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2czoqjlmh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2lrlfghdp.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2eelurzoi.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gt2oivmoysm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mjosdtzw.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gt2wbnsfkbb.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gt2btqeimvn.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gt2voevinfu.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2khnxgyty.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlsdyddf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2mfhtnqjj.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gt2uihwthft.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gt2pkahljut.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2ijgjcfcs.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2evexeims.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2lbnqwgus.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gt2cyihuigw.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gt2fevvewit.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gt2mwawhdjt.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gt2urqvrwyk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gt2xyhsodfj.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gt2yyrfhnct.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gt2dyirmzus.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2gxxzwgfy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gt2mwxwzmvi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ingtdzlm.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2mmtlgotf.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gt2roqymlvn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2lpeyrvcc.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gt2jqufeuap.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gt2qocshjem.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gt2qkhwgxse.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gt2rvjiakfg.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gt2titajwmj.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gt2vplckgsm.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gt2zcguxolf.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gt2hgduhsdc.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2bripfouw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gt2azvhjhuc.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssbcoxio.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmfhsigb.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gt2mkalczef.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbzzapig.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gt2fpiplzqe.html


<!-- 参考信息 -->