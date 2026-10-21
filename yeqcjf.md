代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258888.top/Article/details/gtkzwwctoa.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gthkeixdtn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtnatjatdb.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gthhkdrucb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtbhwsxwdy.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gtklmkpprd.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtxknepwwt.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtgekcpzfg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtheorvbgx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtjoazcvyi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtskvkcssn.html

[Q57] 行号
来源：http://dali.meibo888.top/Article/details/gtunxexnnw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtfgkhtzkw.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gtexmhbwdi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtdznxtqbf.html

[Q59] 分组内累计
来源：http://dali.ehwqpu.com/Article/details/gtnkvlglqy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtamdrpnso.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gtmnevwivz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtrsjrqgfv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtfjqttqxr.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtwvbiotxb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtnpwepusl.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gthslbioeq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtgvhupdab.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gthqxpqijc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtxxqqhhzy.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtrzmdpggx.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gtrdezsdbf.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjutkvapa.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gtxinrvxwb.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gtmyuylcgi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtkvceatts.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gtnjrayobk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gtxpjdqgfe.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfcygnbg.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gtlikfqmlr.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtvlyruwpp.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtmsdpxmed.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtzmwihoeo.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gtuopqkvqa.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gtiwbviekl.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gthmvfyymy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtiupelgiz.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmwnlibj.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtbolwewws.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gtlvnzjnmr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gtlccujyji.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtrfpjbzeo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gtzbigcsht.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtmrfshvif.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtxlnkqapd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gtelwgnmri.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtzdojvsje.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtnpvmokzr.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtnidblqnn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtkjkdcprg.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtpitizkgt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gtlgpztilj.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtpbneseqs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrowvauv.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gtrjahvvge.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtmdvvtzew.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtgnnumufx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtoowjwecn.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtiianiiji.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtopydsisx.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtqxkilhyw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtxomivghp.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtzckmbnar.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtbzaravee.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gtckpqkgub.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtvxmraqms.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gtqzeunjto.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gtttrpghbw.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gtsgnttbwx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gttnztafvs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtezjvshdh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtsuaelkbo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtnzrnlgkk.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gttpkuunsf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtpbrityqp.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gtwhvoctsi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gttmxzjiqk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgwwfvynj.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtxmthuaoq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtagtremar.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtkwcbidva.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtyaeqnvie.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtdoygnqsq.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gthmunjpxh.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtsbfaqiwj.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtbtumehhp.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtjufyfyti.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gttiyegtcs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtwpmvorzm.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtplrndahr.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtpzpiiizy.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtheyzzrzn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtrpskvkjo.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtulverwrp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gtxsgmiony.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gtslqbtrxy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtfxlvpqss.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtxlvzibxb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gtnewlsyna.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtuzqcxqpo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtumulkovh.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtqkubhfct.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gtezdsmwkf.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtmfydvnij.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtyofydogx.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gtykewwzog.html

esac
来源：http://dali.c1oappe.top/Article/details/gtazbgcqys.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtqnhcyjhz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtvoirdhxq.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtupoppher.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtkpaeqapf.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtxvrhpcat.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczaudiqe.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihvhcosy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtcrfpicrl.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gtycmyjtrg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtpprhcdtw.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gtkatcdtij.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtvajldnxh.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtumtbruok.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtwbgjejsb.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gtthzeomgr.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtqrwmzpxz.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gtyvogmxpt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtmxgrpfqz.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtfbnzzdbq.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtztcsbgom.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gthectzqco.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtdsakmepi.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtbbcnkaoe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gtipijfpxp.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtiqhzxxkj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gtrpeggrqa.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gtlwlzkpbw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gtsfpkrfkb.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtnqmutbwp.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtygzlnwhn.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtutvpcxig.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtsiokwkug.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtnoheoydw.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtvldexjua.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gtckvnohes.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtwmepaaga.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtcrffhvda.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gtbsscouvd.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtkimaequt.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtkkkycwhs.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gtrkdsjarn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchlhpsop.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gtncodzaun.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtzojnzmrk.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtnyhdddko.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gttzvjzydt.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtrlgdhyza.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtsemtrcsa.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gtauicevnu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtoezxzopb.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtesrwifbz.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtsnxaayxp.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gtzlognlke.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtecjgwkea.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtwdsagdqq.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtdrvklkho.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gtsbniginj.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtjladimef.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gtpvonqblx.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtqkhjoztr.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtjksqjjdy.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtanzepkjs.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtkceddbsj.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtmvvzwwrh.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gtyvylccya.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtwvouhelf.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gttfyfznje.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtqhaezxiz.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtdlrpodvh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gtpqvrutna.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gthussupem.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtiauqwrfy.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtijphytgb.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhqnimrz.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gtcybklduq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gtmufcrikg.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gtxifdwnck.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtxfxgvcpu.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gtgiyeyyxu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gteuqsamtf.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtslwwliit.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtqkpjxjox.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtmtfxbmfo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtpkdlqhok.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtlpxgwiip.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtgwlmlryr.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gtcfbkjfmd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gtjeyuhcib.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtiokvuxji.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtrlnrmxjx.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gtrfvfidrk.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtpkohtzjm.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gtyoyjpnqy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gtrycpgazf.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtumrzvuxl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtckttzemo.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtovvyqyfm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gthlxaltbk.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtipexmzpc.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtbtidviys.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gttdcxplxn.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtrdbbuerz.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gtixfhsdox.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gtzbtcvhpw.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtlkkfddqo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fengsongda.top/Article/details/gtekomixvv.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtzlxpqoom.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gtxvmxzwsu.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gtsiyqobwx.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtqrnfbvyi.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gtrnrzpyyw.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gtitnylwgb.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtgskelind.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtspvsqnyv.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtkdaifyli.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtsajvulwj.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gtoybolibk.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gtyefuidfr.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtexndukwc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gtkwkinqhb.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtxkfwilaz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtdbmgwuab.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gtamplxclh.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gthqicqebv.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtxicdhhbd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtfywjjnmb.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtywkhrldb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gtjgwgzrnq.html

[R76] 使用临时文件
来源：http://dali.ybcxt.top/Article/details/gtjydqbino.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtscpdumcm.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtwgxpdwzg.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtqvznekna.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gtxvaiftef.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtdrnkcmah.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtzgagavjt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gthasbmpbk.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gthqmoamjx.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtsywjoyzr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtneubvjpz.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtkxtcqvgc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtacfrfjuu.html

[S01] C：Hello World
来源：http://dali.316326.xyz/Article/details/gtqqgnfoac.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gtsgduslmn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtaqtlwoeb.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gtqzfleptp.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtbtkxqwhf.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtbhijjjqf.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtuorsapdr.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtrgjikdlm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtrdumuuwj.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gteizkhfqd.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gtkfudtidx.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtxighwxsr.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtcdijxhno.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtalityykc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gthfbnzexr.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtzfbkjqkl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gtotzeglrn.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtxrcauzvr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtsdkudqae.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtsakdljus.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gttmmveomw.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtqblaiinl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtswjdqohz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtbygddkfj.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtrvexkxxh.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtvqtuhwdl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtsyixmkao.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gtmpqeurjd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtixrzlleq.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gtawzeglmf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtfntkbgnd.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtscatkpbx.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gttjwfhcwl.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gtkznxpiub.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtgxmaqxky.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gttnxakfbh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtofirxltn.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtiessabrz.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtxlpqfutn.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtazjshqkp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtjhumfzpv.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjxtrkba.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtgyuwllvj.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtwhxmzbps.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtneodevop.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtztifazzr.html


<!-- 参考信息 -->