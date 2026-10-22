代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2dofiivtm.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2meffwzrf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2vcmjbwft.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gt2kgkkrdrn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alxqthdx.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggnysebo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gt2fdizuyot.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2hlhdpmim.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gt2lzkwqmen.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2edwxvrts.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gt2ynzncqxa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2yuzrqbur.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gt2gqsrleba.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2roocepoi.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gt2pehvoufl.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gt2xuvpdzxb.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gt2hshghuzj.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttavytuz.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gt2sntqpzac.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gt2hjvegruf.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpwhtwxr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gt2dsnxpgxi.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gt2sgctzypx.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gt2zcuftfhr.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gt2ixwwvekk.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gt2orqdxxae.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2qemougbu.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2ytfqnzfo.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gt2xhzpnwjf.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gt2ypqghjde.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykjdkkzl.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gt2larinrrt.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gt2fwhaqpuw.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gt2ngifjlqa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gt2hnxefavh.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gt2sngsqkrw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gt2sgrqopmh.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gt2fkrqidru.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2kswwizci.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gt2dwjsjmlq.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyxzjoov.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gt2xwwsrvxb.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gt2slkirwah.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwemarzx.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2kllekvjj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gt2ocnvhwgm.html

[Q79] 字符串拼接
来源：http://dali.daxiang520.top/Article/details/gt2umnobzxf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gt2lgebyuiz.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gt2kjzikced.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htkuscsv.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2evtllfth.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2lwmtwvji.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gt2hxfluulg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzaatsit.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2jeauqvoi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2bumajpfh.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gt2fwpzasny.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2exukrdoj.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gt2jakinqdz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgpguqwk.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gt2dyiwgmut.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gaohongyu789.top/Article/details/gt2nyuidtbj.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gt2eoqoczvv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gt2gyekgjmd.html

[Q88] 行转列（条件聚合）
来源：http://dali.xinyue.icu/Article/details/gt2brnmylnj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gt2btnkqzdm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2faryfuah.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2vttqkzgx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2djzhijur.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gt2zxonhijo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svwgueps.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsrzcsyy.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gt2wmyqpxsc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2mjfiuycu.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gt2hogirkbn.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gt2gbbqckoo.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gt2ajzzwdbo.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pojhcenw.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gt2gutswctw.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gt2hwepobgp.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gt2ygisfkxj.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2etnnalon.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gt2zacedzgm.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2dnlvreik.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gt2dmzpnpja.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gt2opznzgtg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wklabtns.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gt2wlomcslg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2vskxhbdp.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gt2bvziumwv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2bxvhhygb.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2odhbzbxm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2lmbusbce.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhfkdljn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gt2ehajgbfi.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2ftmoazog.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gt2ilabmklo.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gt2jewgfuzc.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gt2ektyijlr.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2jgsszsyt.html

esac
来源：http://dali.yangfankeji.com/Article/details/gt2audywecp.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gt2fwajtwgh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2tsqdyenq.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gt2mzkwclhk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gt2lbmupvib.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwhjosyk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2rtfynwpq.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2niglfryn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gt2prolgerd.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2jytjizhw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gt2qnmqpppj.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gt2swndnelo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gt2qlxgdvou.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmppcfeu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gt2ypqdqogv.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2dbobrjti.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2pesbntzf.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gt2yyflrxps.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecuzsiuc.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gt2kspnarxr.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2nnvmfops.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2beynflqw.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gt2qkpmwncg.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2bgtswbdo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2wyyexgel.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2uhtksbhz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gt2klvnjzmo.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gt2wvihledd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gt2cnzfnssv.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gt2xipxvyqq.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gt2qexgjbdg.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gt2tdiamtmb.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gt2qcvddvbm.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gt2kxypmbwa.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gt2rpjrjbfg.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2gaehkqcw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gt2rajgpnsn.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2oxzifybv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gt2pwcrpiid.html

[R31] 局部变量
来源：http://dali.yangfankeji.com/Article/details/gt2wvzjceef.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jilzihfc.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gt2xjeuhunj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2jsjfavwf.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gt2orwifzbk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gt2bggahmgm.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gt2jgcdqxqs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2kcmzzrvk.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gt2zguxgfmf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gt2fycmxerq.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sanchnnb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmxkjxno.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gt2dawywsmn.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gt2mvwuoywt.html

[R38] 管道串联
来源：http://dali.chenlongwang.top/Article/details/gt2jerzczsl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gt2jzsiyxqz.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gt2wufsjmpr.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2rrtpeoqv.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gt2kfhyktgv.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gt2hmqygryx.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gt2dxqhkfcu.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gt2zlpiunof.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gt2mrjtmeik.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2lkewrqzt.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gt2vuoxfyuk.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2suxhqaaf.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gt2oxodpxdd.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gt2ldfjlwxj.html

[R45] 批量删除
来源：http://dali.kuanghao11.cn/Article/details/gt2htnlpqvm.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gt2nobapyll.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gt2rzfpmjqw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gt2skydiagd.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gt2cutnsbto.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2ahiezyrm.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smdgxorp.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2otiakvsn.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gt2ojdubhgw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gt2fohjwdbn.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gt2eapgzhzs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2yhcpxzxp.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gt2hcnwygtn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gt2rxnstufn.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2coeeanuz.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2kxyxpqdx.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gt2jvagibdi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gt2xuhvsbdw.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2onecmfns.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gt2ijtcygfb.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gt2qayhrcwt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gt2lgddcicn.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxvkwvzr.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gt2arejuaff.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gt2dcvuwbsj.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gt2ysllwkse.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gt2smzrimwk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gt2npfqazum.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gt2bxkyrujk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gt2reqxcjek.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2isntvtqj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2tuleffqp.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqnsgcur.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gt2nkaviecm.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gt2lncgxblm.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gt2oelxlmln.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gt2vkuuroqh.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gt2plchxdgj.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gt2yxbgiafh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gt2lfqhrdsz.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gt2euirxezx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gt2idkhhhxl.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ielmglbn.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gt2glyhqqzm.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gt2uoegophh.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gt2kjfqxfpv.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gt2stqeqtjs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2fzetcmpd.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gt2mmkjtfbl.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gt2iyffaubw.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gt2mztqiotp.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gt2rlcxkzdh.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2lhuunuwo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gt2llueiguf.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfssdymk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2dtbxfyej.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gt2evbxgjoj.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gt2uyzegely.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gt2olpmhtaa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2ahmpxszz.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncwnskhg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2hrsshvnq.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gt2eyvylkuz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gt2agphwovq.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gt2szrrlkpt.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gt2gfenikbs.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gt2ngoqdzuv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gt2wynmpwse.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gt2psvhtnyc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckfuudkb.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gt2azfuelmn.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2posczpcs.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcouicre.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gt2kgposvst.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fsebfqul.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2obgfnaza.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gt2tqkbqynq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gt2udyqxuzl.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gt2nogztuot.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gt2xaivyvjh.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gt2xiyzprlx.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2syuidpvy.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gt2lojubrvj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2llpvqjph.html

[S05] C：字符串长度
来源：http://dali.jinqigufen.top/Article/details/gt2vwusinnt.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gt2edykmtrs.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2rkwlecbk.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnvcxpjq.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gt2lvzvpnha.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gt2chylgtgi.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gt2jcvmqjce.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gt2rwmjpxpm.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gt2rqdovpyu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxuvcdsq.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gt2ieggwsyj.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gt2tosipfjh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abykfpvl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gt2phlnocqk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gt2jwcsafzx.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2ptdsooye.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gt2gjkdoina.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2dlrpabyw.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gt2eotdvgud.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwalrfyq.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2whjahrcr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gt2ompejrcp.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2qnkpdgff.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gt2tioplaea.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gt2ariuvkst.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gt2djcpxamc.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2tcdqdfod.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gt2ntsakkcu.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2ahiukyia.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gt2nrfdbsxl.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2shkwboql.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaukoup.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gt2bdaaodic.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2jbasptbw.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gt2aolntwlk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gt2pyuknaze.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gt2butpqiyo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gt2lkqzdekp.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gt2lrygqjdz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gt2nounmywb.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gt2yzfralxt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gt2tvhwmecy.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2pkjmtgjs.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gt2allrfvlr.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gt2nqswtubj.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlqawhzn.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gt2ddauguxd.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkfglisw.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gt2ooeqbmdq.html


<!-- 参考信息 -->