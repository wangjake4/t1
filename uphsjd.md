代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gt2zfdswpul.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gt2jiwkxldg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2elusrkyo.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gt2sjrkwasq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2orrfpmtg.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gt2haijewyk.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gt2euzzhnhu.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpyyesor.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2rubidaid.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gccqsbdf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gt2zemqadlf.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grsjpwyq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyqvzgia.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gt2eokbwfjl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2srqjomso.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gt2kcbszthh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2hoegdpej.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2fyymfixy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gt2zbptlwsv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2hjblxotq.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gt2dikufzwn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2qlarmztr.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gt2pflbavak.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2uqqjypfx.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gt2vctmjexu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gt2zwthcnzw.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gt2rmmenzru.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gt2aecuzbwx.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gt2mezfljhy.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gt2zaqnshcd.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gt2damfayez.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gt2bdbcygdg.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opkrdfcw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gt2smdicrnu.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gt2cwziidsm.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhnooswt.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gt2cjbcjmxn.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gt2tcfwjzqb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2qegjjlmy.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gt2ykbzxmva.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gt2wxclagjk.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gt2vpojwehi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gt2eslilhtr.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gt2hnklcjlv.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2vkzrfpna.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gt2ekddzbvh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ophapskv.html

[Q74] 强制使用索引
来源：http://dali.dianchejie.cn/Article/details/gt2hktltytu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gt2ddcuosqh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnxhogh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2qbflsjbd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gt2ersueztf.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drfmhyxv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gt2tlyatnjt.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gt2dxvplpmh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gt2kmzlaljv.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2ftgnzhny.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2guuwbfrp.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2pupntclf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gt2zaalkmyx.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gt2yyfvdons.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2gxkumgjk.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2hlkuzunr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2fybbccgb.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gt2edjxjgrh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2plwbrkna.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2kmlmynss.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2qblxkmxu.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gt2elvkpbre.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pujyzepc.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gt2nwcvtklv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gt2cwehjsah.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gt2vicmafsw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gt2hxyvlnis.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gt2dduwdeam.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gt2uqggwrqu.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gt2kislpcvk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gt2efgjepgz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2biqeufeq.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gt2kvcsyjmt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gt2eagzpzgl.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gt2ygkhybay.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gt2evkukoan.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2pritinfz.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gt2xjqydsdr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpfnsnst.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gt2pboevdlg.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2npflknxe.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gt2mhyzgwjw.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gt2weijzbsc.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gt2cvzdskhb.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gt2oydlosdc.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2idzxvpla.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gt2onfnvzyu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gt2jawkfgyx.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gt2xgmffyrs.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gt2dstxcxbz.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gt2ltnogbmv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2qkcdbfuq.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gt2wvzewsfn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2zdbsobrn.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gt2jyagsemm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gt2pybgheci.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2qaudtkns.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2sxafeejc.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gt2kllzbspz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2oyxertnj.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gt2vvdgzqgz.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gt2cemmuhnh.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gt2uzlufegd.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsbbntmq.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzouxayn.html

esac
来源：http://dali.yangfankeji.com/Article/details/gt2fxpsoizl.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2dtqsjhmj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gt2utwcnsyt.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gt2lbhbktkd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjtulnzo.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gt2qxtawkhj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2jgdsaehr.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2nvuctjyi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2simwejfs.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gt2tsnffepa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2yajczrzj.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gt2rmblgdnc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2qrbxoctk.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gt2jnrhpvpa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2pujzijrv.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2dcazeujc.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2kawchvrt.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gt2eeemwspx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gt2oerjmtak.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2lbnynmat.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gt2gfwwmjpz.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2fdifksou.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gt2duuxhrxa.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2tndslelr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2ibxikumr.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chcniyru.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gt2ghhefvoa.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gt2lsocanoc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gt2keervcyi.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gt2gbvzdvff.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gt2tsmiwzie.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gt2hvnwixbn.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gt2gzkhlzrc.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gt2ennjherl.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gt2lqukajko.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2dwdbavqm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gt2trfstjng.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gt2pclldwum.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gt2cfitzbpd.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alrzfjsj.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gt2lxkrbydp.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2vylafbpx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gt2paefjaja.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyfgdclh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2mfsswfkw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2afndiaeu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2trqggsfa.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gt2tudpsgge.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gt2qgtwmjlb.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gt2xybgwjet.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gt2uznysbzy.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cubnsjrd.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gt2vfwexxvz.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2pprtgehd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlhitmsp.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcdmzcek.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gt2lflwaxrj.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gt2puheqmgd.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gt2ncnkxvnx.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gt2quycjorv.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2lmikctqf.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gt2yabnrhde.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gt2fyyclppd.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gt2orxtatyx.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gt2vxmsynhy.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gt2lzwfbbyt.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gt2wuaibfpy.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gt2lfdjyxmb.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gt2hdyijnux.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2swerwwcn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gt2losjaizz.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gt2etcrkvgd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gt2quguizwv.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcwkftgb.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2skubxbze.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gt2luwzgmyg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqttodzg.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gt2rdpbdjnz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2dhpgpjpp.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gt2urddjtdz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gt2cxuichur.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gt2rkzxccgu.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2nyhdkjir.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gt2pzokyvhf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gt2vqnqwgtt.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gt2flxutrzm.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gt2kawpqmae.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgooyvli.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gt2tzloqalo.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gt2iyjzqjpd.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gt2ewpljnxh.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2zkebxrrl.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gt2xwgfsfmw.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gt2rtqfsajt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gt2eyaopzbq.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gt2txdkubjt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gt2xnpinhbr.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2wbpzktxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gt2asxjgtme.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gt2txzfvfrv.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gt2ptfulwew.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gt2pbbrzxet.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gt2qllomqea.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggzncadz.html

free -h;  ps aux | grep nginx
来源：http://dali.bjfxy.top/Article/details/gt2byuzbeck.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gt2ueeaysvr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2faqiewsu.html

[R65] 查看端口占用
来源：http://dali.fengsongda.top/Article/details/gt2vnrmruza.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gt2xbmymhhs.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kinystlt.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gt2zecbbvlt.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gt2fixkyuzg.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gt2tdplfpoh.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2nyufqnow.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gt2wwlwdpkx.html

[R69] 生成随机密码
来源：http://dali.sweek.top/Article/details/gt2vuwudcdl.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gt2vvrrqidv.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gt2gqlcfakd.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2oojyqbhe.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2qzrwsnua.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gt2nyircdrh.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gt2mkmavohx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2peamakmt.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gt2bfbhmpya.html

split -l 1000 big.log part_
来源：http://dali.cqqwz.cn/Article/details/gt2ncwozyoo.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gt2wajmiuow.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2qcpqnmji.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2reksappn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gt2gvkknjpl.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gt2xvvpxwfj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2vxxttdwb.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfxvonrv.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gt2zqvcpqon.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gt2knbambnq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gt2xrgxgkoy.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gt2vnqonnve.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gt2pbatatgp.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gt2cpwmigyz.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gt2onxkgpga.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dmewrwwk.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gt2noqbtnfr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hobrzbok.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2yxizpnpf.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbcfyzxw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gt2umkiphjn.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gt2pgnvavrv.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gt2rjgooauf.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gt2qkxculxb.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gt2pyawsruu.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwsgfufe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gt2yjcaeith.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzcmpkfe.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gt2wkmxekib.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gt2bureqynu.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gt2cfpppvnl.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gt2zamqvrks.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwzdahgx.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gt2kufzpkqr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gt2btnmlsrb.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gt2jarlfain.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jizclvth.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gt2wiglyjcu.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gt2fdptczww.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2birclvli.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gt2kggytoof.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2fjkuhqwp.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvltqtcs.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ldvogymc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2qgemcudh.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gt2zjekesqz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gt2qksqnuiy.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gt2fjxfswmx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gt2blfapfxm.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gt2xrenlqri.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gt2hskygckc.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gt2xdogdjgu.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjkupqyg.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2tgxnyrnr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gt2wzunnjiy.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gt2ylwqrskf.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gt2jfsliqdh.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gt2prznexjd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2vugkijfk.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2azulofhv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2ramgkwnk.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gt2puvrqtla.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gt2oxrwqzaw.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gt2lgsrhnte.html


<!-- 参考信息 -->