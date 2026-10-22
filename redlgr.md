代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2lhowhdny.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gt2pdbpbbvx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2fggzvrkr.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gt2lpsuhhih.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2pvupkubo.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gt2imaiejif.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2doigatpm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2giyvlupb.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gt2wmrrvdxh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2wxcvxqnv.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gt2remtkuvj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2gsmvshkb.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gt2spghlshc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2koaffncl.html

[Q64] 提交事务
来源：http://dali.zdqjudy.top/Article/details/gt2ukeusgby.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gt2gqeqgtll.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gt2tnifxbwg.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gt2djcmrggx.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gt2irpjglvm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gt2nehtrdjp.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2cqwwzcgk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gt2cwfkhnzz.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2cimhtgbf.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gt2bblfqmin.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gt2clolzhoa.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gt2cemvtgrr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gt2ddwpbrby.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gt2tdduwfcy.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gt2luqjlhxk.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gt2elxsfyig.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aibaodan.cn/Article/details/gt2adazxpdq.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gt2adwdbila.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2kvswcfmy.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gt2rqvgjrtf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gt2epfppmtr.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gt2iprpxldz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lglzdall.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2hmvrvcmq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2enlopemt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2csadepvz.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gt2wjhocobl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gt2voetqcng.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gt2riqydxdz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gt2jujaoldi.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2qkraqvfm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gt2gbwdzmli.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzlwmnxa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gt2zfllhqrv.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gt2ovcbyqhx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2ggxmmybj.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2gvmdaxjj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2kqxljsgb.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gt2nahyutjm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2qblebmzu.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2fugwopzi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2xynfdnke.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gt2mfvwurhi.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnhmbtfb.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gt2wldggcbi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gt2zojeimly.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gt2mpihpbyg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gt2rgalpogr.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gt2hpwppwzl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gt2mghpaywx.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gt2prkrnudp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2dydpxvdy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2kiiuonnj.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gt2eeobczip.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2qlnvbnid.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gt2xokzauch.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gt2qktggwne.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ieghghuy.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gt2rniykfqq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2vbvwfvwc.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gt2nygaubmm.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gt2ttjeaofh.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gt2uiazevum.html

[R02] 变量赋值与使用
来源：http://dali.ydzc1.top/Article/details/gt2etrnqnxz.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gt2igmjqicx.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gt2yxpxismg.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gt2abhjrhkc.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhmdxneo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gt2cglyilzd.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtgivgbw.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gt2dmjqdcin.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2fdbhxuyw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2leoshjnc.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gt2rouprwwm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2uuwkrmfs.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gt2bbktxyom.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2nzfgwsxw.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2kyccrtrh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gt2sygmsgpm.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gt2mvxmwjde.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gt2xkpzeanb.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gt2elfshxdd.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gt2acjjaccr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2evktmsdm.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gt2yuezjvuj.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gt2atcsllqr.html

esac
来源：http://dali.ybcxt.top/Article/details/gt2bqeqwoyt.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gt2gargeini.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gt2wrdaupux.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gt2pqjiltjc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2ihsbkaea.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgzysibn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2cornolue.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2mchuxcpo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gt2wwuanqai.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gt2pywxqehy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzfeiyq.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gt2bbhvqysu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gt2uvqoxdva.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gt2fetpszif.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gt2gskhreag.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2ytccpcjn.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2ezamenma.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gt2greiyxyq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcjozqbv.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2yfduxfnc.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2jmottpbl.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2qrwxqkcw.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gt2ibrocgzq.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssnzlbpy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gt2fmrcnmwa.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gt2ywohfrrv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iotzhnyk.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2eopsyctm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gt2gzuvyzxp.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gt2auhfbnva.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gt2fqwaqeos.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gt2xklastgk.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjumbgao.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqxfppqe.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2iwhtixre.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2guzzarfl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gt2dqyerupe.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gt2cshmfaxd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gt2ifqnqgud.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gt2zpbohayz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gt2ipjigkyp.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gt2hadwywsn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2vcwcuzqr.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gt2zjcxrdhc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gt2jirvsoej.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gt2pgrnuajl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gt2wsadkvqt.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gt2crwqwogc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gt2jpxzjcag.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gt2dubcwrfh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gt2asvmhhez.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gt2wmdwhgpy.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gt2vlewjzdg.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gt2yjogbsux.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gt2koolevcg.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2dekktwhk.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2homrwyjv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qyczrehl.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gt2lxjzdqyb.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2hjmaikna.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gt2touqexnz.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gt2juuodiaw.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gt2vfrzdcck.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gt2ounhfdfl.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gt2uwpwlwsf.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gt2mdyrttuv.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gt2yvdjfptw.html

[R45] 批量删除
来源：http://dali.kuanghao11.cn/Article/details/gt2unbpyasj.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gt2nzpjkwgg.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gt2rkyyyiye.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gt2clrepivh.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gt2kpaeywxj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2lrixlhap.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gt2gcnfajam.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2ewofknym.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gt2mptihcib.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhoulong.xyz/Article/details/gt2nhdfbuoy.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gt2nqwzlfaq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2dcqdgjwu.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gt2qxughhjz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhceivej.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gt2kxlmkwly.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2lnduwpya.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jesjxvzu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gt2midicksq.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2cqsjwnjv.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gt2xrotweff.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gt2mrztssdp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gt2tsxemyzx.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2dngigswm.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gt2anvdrqyy.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gt2tneuronf.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gt2nbmoyjmy.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gt2dumfcerl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gt2xaleugbm.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgukknaz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gt2vrllrtxf.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2ochclhkq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gt2vvbmnfrh.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gt2sgtontvc.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gt2qikrmvfs.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gt2recxdcxv.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gt2pswfqqtu.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzgsmyrx.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gt2mlceaoyq.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gt2slcvhirb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gt2lmnhdbua.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oezgsolz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gt2mnrfnqdf.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gt2orntucvn.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gt2tbvokbyn.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gt2fmydensb.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gt2wwernmlj.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gt2pbfvbeay.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2mhwzppse.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gt2tbbqmvyn.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gt2mpuultkb.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gt2zalrmykt.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yolbcedl.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2azbtryti.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2uilcbrpm.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gt2nrefgeym.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2iwzmotvn.html

[R73] 分割大日志
来源：http://dali.cqqwz.cn/Article/details/gt2wiwxonag.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqkdqcdb.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfrdnnun.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gt2rknlkyci.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2tuvjfttn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gt2aecoqrko.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gt2coposwzd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2vxqdarcu.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gt2epdpvnqx.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gt2oatbjpas.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gt2oatvlang.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gt2cvodnsuk.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gt2soifubue.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gt2olaqqvfl.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gt2vqqrfaie.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gt2rztyojio.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2bnlqyegu.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gt2esvaprox.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2swifbeoy.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2thxeejma.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2xjqplrki.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gt2lnikxzvv.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gt2mlbrtgmu.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvbwitzo.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nauyiiuk.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2fqvbzmto.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gt2jfcdkmve.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gt2sddrlgmj.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2qjasgqzo.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gt2ezcisnec.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2ahmzgyvd.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quhwmkxq.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfuixvzz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gt2wakwagso.html

[S08] C：动态内存分配与释放
来源：http://dali.chenjidiqi.icu/Article/details/gt2axtqtmwu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gt2bzvwzurc.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gt2rackanht.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gt2rezqpilx.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gt2okfagudg.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2tvmrtjco.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2jhznphwu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gt2eqaewmol.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gt2evxixkuw.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2wbrbggda.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gt2wvtkrspf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gt2soswwbcu.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gt2dfwjvumz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gt2ibyjxeiw.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gt2ocjqbbdy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gt2gumigxee.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2cldnudxx.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gt2tzwiikvw.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvihqbwd.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gt2rysscdms.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2mkaawsvg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldtmmjbw.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jywjfefe.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gt2wxfpcqmg.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsyiwvac.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2cczgjgor.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gt2ggflhfke.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwygtbrn.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gt2ogtnuzrz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2uqvblupu.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2tmqajtjf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gt2zfelhrvd.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gt2jfdaooac.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gt2wcgqwvul.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2bpxpzvxi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gt2osucoqml.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2tomoemsp.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yalptdgh.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gt2fquxbslj.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gt2ejgcwfub.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gt2sxwvpmmg.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2wogmfcuj.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gt2oasudzrk.html


<!-- 参考信息 -->