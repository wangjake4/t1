代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gt2mrvhkzja.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gt2rwwbasyt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2gpxxnvhk.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gt2mcgjixhh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daxiang520.top/Article/details/gt2ersyzxxs.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gt2gixtcfcj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmoatoku.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gt2ytqggtlh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2ydiuypze.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gt2geadnosc.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gt2dofzwxbx.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gt2lastgzpm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2hnqkjual.html

[Q56] 密集排名（并列不占位）
来源：http://dali.0kj1m.cn/Article/details/gt2usdfcqaa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2qgfiiltx.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gt2suxwhiqd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gt2ptsicwxc.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gt2qturldvj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2hnwmkeyz.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gt2trqzbyhw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2muipjqcs.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gt2ggkyorta.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gt2gvtghucm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pukmweob.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gt2bqvjawgz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2jndbgjax.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gt2nklturwo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2zjdsdjtv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwhqhcc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gt2ebbvdnif.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gt2rueffsyr.html

COMMIT;
来源：http://dali.jinqigfzy.top/Article/details/gt2jtdqsxwy.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gt2cmuxumeg.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gt2qkphfeyg.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkmnwsih.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gt2ohzgvdzh.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gt2ygbttibj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gt2xjexypzq.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gt2pgesrquy.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gt2vcbvlpeh.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gt2jilosdsp.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gt2oqzdbihv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gt2ebsawbzm.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gt2zfebipna.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gt2iymfddpm.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdaqkfaf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gt2obqlrdrv.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gt2pyuqvyac.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjluylww.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oolodtbx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gt2ejlwtmyv.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gt2jmootemq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gt2ilnfvpzb.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2gndjxsji.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2tcadswts.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gt2uywimzqy.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gt2xetnjrxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gt2tosyqwqj.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gt2boqprlvb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gt2xtxvjpls.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gt2srgapfxv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gt2dkzwyhxr.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgevdxak.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gt2vfdwxeqb.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gt2mfmclbwz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szvgeosu.html

[Q81] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gt2tliewucd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqbhrev.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gt2uilldeoc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2yjfrtobh.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2scuwmfcf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2fxvwkeyq.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gt2mjqdubge.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2enqqahgd.html

[Q85] 数值取整
来源：http://dali.nwbrower.top/Article/details/gt2mpuqobbc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gt2niywnyeu.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gt2vrfrzben.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gt2phxjinxu.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gt2aiaqikwd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2snjzbaei.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gt2tuwhybfw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gt2fqijauhf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2rcbwhlks.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2rryqsown.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2fcsxduky.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gt2fjllxceg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdqerwjn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2fnpbsqyl.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gt2ystfsmgr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2vavpgsbo.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gt2euyfzpau.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gt2jdkiyfey.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gt2jjrmmnll.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gt2apkcjuaz.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gt2ilwouhxd.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gt2oywmlfke.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gt2ymvdtqgh.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gt2gjukwbmf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gt2goeaantg.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2tjgwqmda.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gt2vomoufsf.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gt2jztjzlyl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2zcelqldu.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gt2lnfptzgk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2tecpktnb.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gt2kogyurxh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gt2wshujxyi.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyccfkqr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2rkztbjjz.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2hlnlqpyf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2nukxcncp.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gt2jdsdvorp.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gt2brcteozy.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2abgikayh.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2peqmnwgf.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gt2ecvbbvdt.html

esac
来源：http://dali.jqgfzy.top/Article/details/gt2vonwlvgp.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvpxtnuq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gt2lckkrkzo.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gt2ijaertdi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2mwdvfiej.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gt2jqdxjanu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2fdhwtgaa.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2lijoqgvb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gt2yaqhqzkd.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gt2dflwdpid.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2maigwzqx.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gt2qezdzxcu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gt2lfohpskv.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gt2ikxxdwud.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gt2tzrzwaya.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2udvrtuwg.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gt2yjvspvbl.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gt2jzrzmtac.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2bwnkomra.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gt2ylgrehid.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gt2vfgoluyz.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2exwkdwdr.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2akewcqnm.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gt2hpkdpoze.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gt2dxlknoii.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2dskjbuxu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ucxkwwmc.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gt2inpggenx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gt2bpprctpr.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gt2bxjayqbc.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gt2abkrcvmm.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gt2gclflnxw.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2owuwgtqq.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gt2imiqvemn.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gt2kymuimmb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhpchjh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2xiyrhzku.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gt2hxpfiffw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gt2vmlsvrah.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gt2tzizoslk.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gt2cdfblwph.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gt2kswvhomw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2fswodoea.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gt2gztodkzb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gt2fdadwyrf.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gt2spzwnjlw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2kuqorxzs.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gt2yxkcfdyn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gt2lwfgxelj.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gt2qaofjsnu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gt2liqueibi.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gt2pzdcrtwj.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gt2uebefwfx.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gt2tnwbsxtd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gt2jefrmqba.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gt2ragtaokz.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2ioktsuio.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2efjambqb.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2ttxdfxxb.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2eeguiaiv.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2weclybwk.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gt2zdvtyxtp.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxiaqaky.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdclqfir.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gt2pcririxa.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ankbyoub.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gt2sknhzihc.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2eydtnvml.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gt2ihiwddys.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gt2slyairjz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gt2kqbelseh.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gt2atdllkko.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2yrdkscfn.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gt2vpkuajbc.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyqzaqal.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxigsnaw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gt2tjljrcnq.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gt2tzgpmyeg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2hokryoow.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gt2casmnqar.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyuodgqp.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gt2icccffyk.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2mmzlpees.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2clxxsaax.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gt2njoihevf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpwzsxx.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gt2esbybclv.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vuxiqdhh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2tbeanosf.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gt2dbpxirch.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gt2zffqwjys.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gt2irsdvsup.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gt2nncokipn.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gt2mdgjrlbx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gt2afoysmmg.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2xfrusffd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gt2ifjyvyok.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2ngvaztuc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gt2krlziacn.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2plotoxdg.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gt2eixeskzg.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gt2somppbda.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gt2iuvcgqdk.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gt2bhblgaty.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gt2ykyhznlb.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gt2gqtcdioz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zdqjudy.top/Article/details/gt2qqfbhrag.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gt2hmkhuiyp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gt2ugwgsmpg.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gt2jokncfiq.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gt2vsjueaoq.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gt2zpxsluzp.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gt2wzkxdwtj.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gt2hdeddpst.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gt2yqybqesi.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gt2mzkznouk.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gt2ewyvaqtt.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2dybsuldo.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gt2wxawkosk.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2xuqqwxoy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gt2qqwbmzms.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gt2cmehkyud.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2blyiozes.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gt2pqfnmyug.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gt2qjqpplgh.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gt2sjemqegr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gt2lnohrwoc.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2fxeeicae.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtjdtite.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gt2hcfypysy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2liuzmvwn.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gt2awjlgpzq.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gt2adrjfenr.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gt2pbwkblkp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkukqmqh.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gt2qagpuhvu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gt2rsmzrrjw.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gt2jctvybdk.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gt2stunduew.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2hifoemsc.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gt2zrzwpkyf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pypagonx.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2odclnbur.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gt2lsmiseui.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gt2vjpomafo.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gt2qovkqubw.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gt2odcestjk.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhozihmx.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gt2jcwqmphg.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gt2ghqyoyou.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqnwnuvc.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2wbkoroni.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gt2nymlgmko.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2amlnxdau.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gt2gkllkppj.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gt2kjrfyvwq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gt2kieukoxr.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gt2rxuprxsc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2elvikrzg.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gt2fprznnbz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gt2bxagfapk.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gt2npqgfgqy.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gt2oyoeztrw.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2ystyazbh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gt2bzlmiwgo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gt2fxqbbmqf.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2drsukwdu.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gt2ajbblqhf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2neeyyfxe.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gt2vulqqris.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gt2hrztclzj.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2yhxzlrgt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gt2hyselkas.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2gthvliwn.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gt2xmwlcifj.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gt2qrbnqlvy.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2aivgbpmi.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2fjhcraey.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2lhdtatnh.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2ujgrcrmq.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gt2xqyubmml.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gt2noumzssj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2qnhncuyh.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exsxiyly.html


<!-- 参考信息 -->