代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2arfxvdxv.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gt2jqshvurv.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2wriarxli.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gt2htbllpul.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvtpboff.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gt2xboobvgv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2xmftspej.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gt2huecdprg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2joxbtfiw.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqvxgztv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2icolqrmk.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gt2yomchill.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2nkgupsjm.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gt2iiknhegw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gt2lazvfbxk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2eaavinjo.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gt2dvoqldvy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2qkqutlzz.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gt2bxeogzie.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2rkpktups.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcnfnqog.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gt2brduorsp.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gt2sqogntse.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gt2dwkzrvmb.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gt2uctesmrt.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gt2huffsonm.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gt2pzgerqjx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gt2vvspacjg.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2ekmusxgw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gt2ranccxpp.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gt2xnmftkxt.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2vvolxbhi.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2qdookaid.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gt2tvzkubti.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gt2bousvuuz.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gt2eutxzxns.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gt2fapoqhpe.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gt2ycigfdid.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gt2pbgoqmeg.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gt2mwpftqgr.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibjedcwo.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2opmaavte.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gt2jxavlsse.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phtirffk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gt2blhsryvl.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2ugqyvhyq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2zkwwnvex.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gt2jdqzyrxc.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gt2uovzdpgt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gt2tscjbldo.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2motngwhc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gt2hswzwryf.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gt2bbvxyjfw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlvvljbw.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gt2mhbgempk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gt2zgyxtxlj.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gt2qfliewrl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2lrbpakqz.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2zxjqesuv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfvpldjs.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljfbndhy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2kplgpoeq.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2zeiboxqo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2vujigofy.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehnpsoym.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2hrrkdkkc.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gt2pkzayelw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gt2aiuwvrwp.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gt2tgznaufq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gt2qcvhianb.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gt2vlkhtkov.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gt2xvqsbezh.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gt2cudcyzal.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gt2mdogbzpn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2tdodwxsg.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gt2zwpoapme.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2lwwbshif.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gt2wrnkapdi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gt2gugilrdk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ienppckh.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gt2omvnfoee.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2zlicmwjg.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gt2ukmmgmqh.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gt2rccbjiks.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gt2malmcmll.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gt2wbeqfrpc.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gt2iptshkff.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gt2hqehzkeu.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gt2piueznpr.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zembmmaa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gt2lijdevfj.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gt2mrsjymqc.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gt2ijvnmlhy.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvxemzdn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gt2tlcpnkyr.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gt2wnxhkbws.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2zrbuywji.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvmtopyb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2crqqnngb.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2jdhsrfuy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtcipgwv.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gt2gnjrmgfw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gt2soymrbey.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2zktnuvee.html

case "$1" in
来源：http://dali.hnxiangtu.top/Article/details/gt2xwffaimg.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2mxmkcrzn.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2wvqaguom.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gt2pkmmnqsq.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2avorlqqx.html

[R12] for 遍历文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ljpregfi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gt2jywlmyej.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gt2ugqgvmvt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gt2fbjxcqqi.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gt2ntqeaduf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2jiszjifd.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2cpmmnmaz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gt2gjinapyr.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbmsdhrx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gt2qecbmlkk.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gt2quwfwiuj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gt2mmdieete.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnrbrtvy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2taltexda.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2acwfzwtz.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gt2ksurcdrv.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gt2ayorspun.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gt2wqhwferl.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2xhbwyhbs.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gt2bawejxdc.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2lasibgtl.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2luoecust.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gt2vtzepqwi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2geqvttti.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2rktkproy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gt2ikplhnaa.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gt2oofuegju.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gt2dknmuovy.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gt2ciisutsh.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2agpqfucj.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gt2frkzotoy.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gt2pnrvflaf.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gt2mmokqmnk.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gt2nqovmmct.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2vvgvenje.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gt2bgvlcgad.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gt2purffhpa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gt2tacfqosj.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gt2cokmatcn.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofinwvag.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gt2cjdcuhnl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2myvollvs.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gt2szjbkzfv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tianlin.xyz/Article/details/gt2ebtzwrhd.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gt2yjiwoort.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gt2lelkrefq.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gt2lbxbhbye.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gt2wuqxveyf.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gt2tlwdhzvv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gt2ojpauweo.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaiqqvqk.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgxmnzal.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gt2ucadjdma.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gt2rcxfebgo.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2jqokbwqi.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2jyjdkyeb.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gt2usmresyk.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gt2ecfajjqc.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gt2ligommmn.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2jxpezjol.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzfebbxj.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqosfeyc.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gt2ssczwnfc.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gt2wmbtrddo.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gt2dbjcuohq.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gt2uxdgptdy.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gt2nfgyuoup.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gt2mtczysco.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbhvptvo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gt2tqoxwvvp.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gt2psaxcvpi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2ucoocicn.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gt2lvmkivdg.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2dvqnshbs.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gt2utcpeubz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gt2dsutjtxl.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gt2jtmnnomc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ncuymwjw.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gt2lglsqgri.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2recgqwsl.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gt2tghkicfn.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2lupvohbs.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gt2zwxiqxus.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gt2tdocqwop.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gt2jogwjxea.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gt2ydvqugpj.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtokowfl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gt2ohqdgian.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gt2hygojqxa.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmddurxe.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gt2xlqxejcd.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gt2hcllqlli.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gt2nzbgmqpy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gt2lnmywmue.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2nbxuvtei.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gt2cqfenmwd.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2xukzplkd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gt2ujofbcvh.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gt2mygtioie.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gt2pxkvqvpv.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gt2vwlliamv.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gt2csvwqttm.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gt2deiihndp.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gt2jjhiqxbp.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gt2jdstozoe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gt2gdnjlcjw.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gt2gchxrfwb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gt2uvbeasat.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gt2papbvmzo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tbivwvum.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gt2qptczxam.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gt2gfgpibyj.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gt2iatqrnxi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gt2ohnywxxq.html

[R69] 生成随机密码
来源：http://dali.pycfn.com/Article/details/gt2xlboyeqe.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2xbtsamvj.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogybxcwm.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gt2ulccgkdz.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2fhtiujxa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdoxqadb.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gt2biaqsonx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2xyxtxnrs.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gt2brjsbphl.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gt2oxabugjg.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gt2fxizfslq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gt2qjfqjsoc.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gt2vntkdmyh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gt2wxtblfec.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gt2qnpiyaez.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2phkuwxlz.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gt2ycdtjslm.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gt2zadluwze.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gt2hupbgnne.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gt2ypgqtqse.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gt2sararbvf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gt2ywwodfam.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gt2eywyskpm.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gt2kpwnmisj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mothlsok.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gt2nigmjdau.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rddtcupg.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2rioruovd.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2ipddbrmm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kkbyqike.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2qswdpfxr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gt2dyobybnw.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqmrbjvz.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gt2mkmppjcy.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gt2okjpimtq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2sqgwqfqh.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2qxgtoejn.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nixeknfc.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2mvivwxou.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ictbdfcv.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2czxrbado.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gt2hqahwpnr.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gt2qrwvewwg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gt2iuzzaivj.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gt2wvbctsnw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2cpsmendv.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gt2abexpoci.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gt2xtvgvjak.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2oumruulf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gt2tseyvwxg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gt2yjneqizv.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2seoqzwza.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2acpjpyrp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2tqiwelke.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gt2tuauoplq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gt2yemtrwiv.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2afmaehao.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gt2qgvqsyws.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2cwbotkjr.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gt2oexarpjm.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gt2vnfehoaq.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2womeghpd.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2kqmjnwch.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gt2xkgtvqvb.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2iwtukksq.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gt2gzgmrbyh.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gt2xdguropl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gt2qnrjgfpl.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gt2dflqueyi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbnomcdq.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gt2wxulgqbv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gt2eaioobzg.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2vkqwtkdz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2owaaolmc.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gt2zrkkfeqe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gt2dibltkyv.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gt2snonkpzc.html


<!-- 参考信息 -->