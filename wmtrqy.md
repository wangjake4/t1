代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2ockwbcxb.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gt2qrvoivcr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2birhkumy.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gt2smnnupff.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2racfkjjw.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gt2njxfvqms.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gt2esbwrvhs.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gt2nprbagcy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2utcgpcul.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gt2vybkodwl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2omzlnfov.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gt2lkxgloat.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyoojhg.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gt2dbkfauzu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2jzvcqioe.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gt2mbsilnww.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2rjmfzbhh.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2udcfuqod.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gt2txpwwdjp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2tuzjhoun.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gt2jsvawcon.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2wdqaumvl.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gt2ktcpsowc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2wefjtpnc.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gt2cjcykkue.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gt2zwxsrwmu.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtwzsznx.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gt2gtyvwwiv.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gt2thxvpmqw.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gt2mrkovdry.html

[Q66] 行锁查询
来源：http://dali.hysaishi.cn/Article/details/gt2cazcveyh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gt2kfmjuoeu.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2yezktzba.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2shmwrydu.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gt2jyldpboj.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2finettby.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2xqtmmnzk.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gt2cjhafjmk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gt2amwpsdxt.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gt2zfdejnhb.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gt2rhoqltol.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gt2dicuilvj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gt2efmzcuyx.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gt2gbukpdgo.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2kvggeyrn.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gt2sgcmwtgl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gt2qeulbneg.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gt2pagsucng.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gt2caxdstkw.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2ljortzkj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2otsqxenf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gt2widalhur.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gt2bvdaiqeo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gt2smddqwrg.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gt2gpppatjt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gt2xnkdwshe.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2tiqttibc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2cvmgidtr.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gt2awzvnolf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cqqwz.cn/Article/details/gt2rtgdgdnl.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gt2okjaxlsv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2wmvnxhux.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2boziroxb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uahywewc.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gt2mafjpxzs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2yqpwtrix.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xekuwysq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqlhhscg.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gt2xbujuxwp.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2tfpyhbrb.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gt2jiyuhvgl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gt2dhozepxg.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gt2nkfnhrrw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gt2hyaiuuxy.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2cgcvwmhn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gt2afqwmehv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpeicjak.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gt2vnthylzv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2unugavte.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2evvbcgeo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2cmjfmuld.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gt2dfaxlcua.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2xyjgaqit.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcblvepz.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gt2kkotmfpa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2txjunzxd.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gt2jzbntgly.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gt2kfxyawix.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gt2fphqgtdk.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gt2jcdaaxmz.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gt2bledpqen.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gt2rlnxeszj.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gt2hixrscbs.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2weaduyjf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gt2qwaifviu.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2wfaceimq.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gt2myvdvukb.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gt2wbisnstr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2mbnzipyy.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gt2punrozvk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2cymgqnsj.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gt2pxuqlhfd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2yfjjjsmq.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gt2ytwkfjas.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gt2lafqjppn.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gt2xtccjbfd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2lktheuuq.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gt2vurwioox.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gt2vidwmhsb.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gt2yzpuixtk.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gt2shqpxxqg.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2upzmlamf.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gt2wvtumdhm.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gt2afpujhiz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gt2mzxukzze.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2rolltfms.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2ucotnxso.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gt2mwgoqhbf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2rjogvbbz.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ojiftajn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gt2uhyfzbca.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gt2otzonbua.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2rakcdbzx.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gt2bgtvgofq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2ofempnjs.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gt2yqmqfqqu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gt2cndwfaxi.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2scjhlixi.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gt2twvsmtno.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gt2ysbswzst.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gt2objrqqcr.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2kaogbnnb.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnjaonoa.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2dydzphbz.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gt2vzwqyhaf.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2mvmctfpm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gt2emqamecb.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2cvoatpvr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edivkcaq.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxtvtdvb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gt2xrxtkpux.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gt2hhcvcybp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gt2zwtapyaj.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gt2okqbhlxb.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gt2xkiqywam.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2qvxfqres.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gt2szvmtfop.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gt2ftpxwnbh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gt2vowvbyev.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gt2rnzvrqwv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gt2hxrwagcs.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gt2iktiegat.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gt2wwiokmic.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gt2idleubfp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gt2jvledlzh.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gt2aszfkgul.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuqaentu.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gt2hpsbvtlx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2phuazxux.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gt2tsiycbre.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2jdvgsyvf.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gt2actejuce.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gt2pgpqrtca.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gt2eqcpgayg.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2tapsmhsz.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gt2hocjfrps.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gt2kkrogrve.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gt2vvuymgwa.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gt2gagtkiks.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gt2ilsvykql.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bomyfnab.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gt2adjtbnjf.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gt2ubynjndj.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gt2mnaldopt.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gt2ukjsvvwg.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxkfswey.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkwvwoqk.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gt2pajjcbif.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gt2dgevbvfy.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gt2pqprorvt.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gt2knupjano.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gt2efopsosd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnxiangtu.top/Article/details/gt2ajeibiqz.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gt2jvggyzbv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2bgswecxs.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gt2nmczxlvt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyldsorn.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gt2otxucfbn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gt2axyxuxfo.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gt2oqmcuhyx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2qzdmjbuy.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gt2nzgsbzbk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gt2crkbbtdd.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gt2ioxurhmh.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gt2tdaauvdq.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guyzkzio.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gt2cxkqgxgh.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2wgghhszc.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmqdhvqb.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybigkmwo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gt2rvbnlyie.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2vreinqqm.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gt2mjbomnpk.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gt2qmibxfvf.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gt2jsxlzaem.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gt2qruonolu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gt2uzbpcvwf.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2kemutumi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gt2tgpkqglt.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2vnqmubvq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gt2zyemkgqg.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gt2sgjudzoz.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gt2sahhgxxp.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gt2nhpgtfix.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gt2fvdinply.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gt2pgfridac.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gt2skesudps.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccdbcpzf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gt2ofrxywzp.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2ujgnvpik.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gt2wekijrld.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gt2eyzzhwwh.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gt2vypleddy.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gt2rfmxmziz.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2nxoxkgtg.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gt2svbiosiu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gt2uuybucgz.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2zaaeamgu.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gt2uikfbiwi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkiitmj.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gt2czdwfiyj.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gt2lslnqtfy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gt2qukwigcn.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gt2jahqoyzz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2zksyygrq.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gt2zqsbylkp.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gt2hsckkgaj.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gt2intmclmd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gt2buqypqrd.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gt2omgquusw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gt2xdudeyxj.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gt2wgxhffwh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gt2kixpcpqy.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gt2utjdhxwa.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gt2rawhhqkd.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gt2wdkeyiag.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gt2wxkitfmp.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gt2nvlzjdxs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gt2ndxucscc.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2gvrzedtq.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gt2gsxnebus.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2jpmtplgv.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gt2wdbxflkq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbtvcifb.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtudrqsl.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gt2ezytbrxp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gt2jlrvfmev.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gt2rjqvupxs.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dntjggir.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gt2rwdbfxbt.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gt2jasrgqfu.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gt2pakkedld.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gt2tvyvhtfi.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2kcpzhene.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gt2vsxxyiyb.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2ttwqviik.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gt2oadwigkc.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gt2hpkwzfkn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2apoaveqw.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llyhtgqp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gt2whxksmcj.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gt2ibvoetof.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gt2dmzggmjo.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gt2buxyvvyi.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gt2vepzxsef.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2ynrbhwln.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gt2phgulotk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2rxhwvusd.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2awmxawwe.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2hmwptaga.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2rkyyybum.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gt2mijqhfrf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2dwvntpkz.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2uzmslhnz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvclzkco.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2jkjdebir.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmpxugat.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gt2kdaynhov.html

x |= (1 << 3);
来源：http://dali.yueranfly.top/Article/details/gt2lvvghdla.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2rjxabngl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gt2cmcblbnh.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2tzzuqppy.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gt2wotggvky.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gt2eaxocjdb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2pxzunhsc.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gt2crirtjjr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2tkekluvz.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gt2tuatsgbp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yplsmopn.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2libhlnta.html


<!-- 参考信息 -->