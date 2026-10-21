代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtkeeenbbe.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gtgejntnik.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gtsngbbsyv.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gtwqausqjf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtihapujvj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtlkmcwfwx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtpodpimme.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtoiyajnnc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gteqhiksxj.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gtifasaznx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtrlobcker.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtqtpnvjil.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtzonmbtmx.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtsvogcwli.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtnscgvuxo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtegzruclx.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtglbvsogh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtmszjcjbb.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtfhebherk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtshxumpqf.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtmpnzaiul.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gtrgtyvsuo.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gtasmyzjus.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gtxkpenaby.html

[Q65] 回滚事务
来源：http://dali.fzhhl.top/Article/details/gtqhopshxb.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gtjpznimnt.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gthzkllbsh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gtcyklvnkx.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gthyxgxvey.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtfdydotuh.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gtwuwrygjt.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtxqqotwgr.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gtgmzicuky.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtldwkidsl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtygjcsusc.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtrfmmwjru.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtamxazjin.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtnpuyhzep.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gtkgkdfqhc.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gtjsqyuwnb.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gteuphutih.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtqitcxzrm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gtgymznjwo.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtyskddtov.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtteqnptxb.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncniffxn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtjggwgguk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gtguumbejc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gtbhkwjrzr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gtstazdvzv.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtsinmeykc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gtpvrizvif.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gtkaypkqkk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gtseexhxzi.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtopioycgk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtxlqnunje.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtttqqlmsj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gthldazvbk.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtqpvvkuaa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzphhlutc.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtqmakpcoa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtuszbbipi.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtfswinzsm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gttorztggo.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gtdsqtlrek.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtfmxqudnf.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gtfjiqvxuc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtsyixlsiy.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gttjmcjeed.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gttqabrpth.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gtuhbdaenn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtagdecirk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtsfwhveag.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtsjxfkndb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gttvtckhtl.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gtwpkbhhcs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmgbrggg.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtoeouxegq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtyqbufmwo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthpemkbss.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtuhvmands.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzhceqgvm.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtgvlnjgzr.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gtjmefophq.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtmlgmajdf.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtszsufusd.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gtoviiiorw.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqhgqfqw.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauesjqct.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gtjwgrrten.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gtxvxoxnsn.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtpfzgvgnz.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gtmvvytdxr.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gtgsuzdbow.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtaedshvti.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtfkngktqv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtgcnmvlps.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gttxqtcwse.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtbviclubf.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtoaivbugd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtpvpgatrq.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gtoyziljbx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtosebkgfk.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gttobjlbqb.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gtxoseopst.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtfcwtgpou.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvfpznuj.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtynonneqp.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gtdmuivwwd.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gtkqthfbpm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gtuhdajitt.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gtcuywizkv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtncllnnvc.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtjydqzwsg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtlzacstdy.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtwneqlsrj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtmtisipni.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gttadikvat.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gttsxifegg.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtkwmvlfdp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtcisbrabc.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtpsjvazko.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gtvhkdfpdi.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdvbhxmk.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtbnykvufg.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnguezxc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gtjntpfjwx.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtvlflaret.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtfidykqvt.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtxrpajoxk.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gtrmbcgbyl.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtudwmdacj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtbqixeftj.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gthejzannq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtuihydtol.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorsrgivf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivqckjtj.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gtctytvcrb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtmosxnmey.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gthuvmvvsv.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gthzjurikh.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtqqmdsegs.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gthwzqhwlb.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtbpfasitf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gtagjeoleo.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gtzokyaobj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gtqhiprkpg.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtnthwsdhq.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtweespvrf.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtrawoigjf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqanhheas.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqpvkncc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gtnzawgcuh.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtipidnddp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtbmtygoel.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gtqrdcutwe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtuldpdxix.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtgyajhpyv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtqrzvyawy.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gtigmykoxk.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gttqeylivf.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gttvrnapxd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gtxqxtccer.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtclbqiqvk.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtuufcvnwp.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gteasqxpcc.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtezflhwen.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gtqcsujhrn.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtklveynqf.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gtcnfdbcul.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gtevmfosqk.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtupfotdkn.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gtmuxmqgsx.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gtxmswzusk.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrqpmxgq.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtdlusrcok.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtuqovyhjq.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtqotlupnm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gttqmvmreo.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gttthcatwv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtvvdormhk.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtuzhzpgby.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewvjbxrq.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtlgzrijbf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gticzcqkkr.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtksgsphes.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gturvrdkvf.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gthwbhruxr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gtzfhmrrzh.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfricidw.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtxsuawosq.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtbbhijciu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtiifqwecu.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdwszanka.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gtwqccbwvx.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtvtalzlzj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtapebqume.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtsjynzvts.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtcmhuyeny.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtsycrbmue.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gteazdujyq.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsclccdx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gttdktfvvh.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtwfzqiars.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtdaiucffr.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtwdtvjrrm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtivriobhd.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtgaoofutj.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gtqfbskagl.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtmturusoh.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtcgfdmxfv.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gtycucjfui.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtozefmkzc.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gtibrpbjxe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gtxosgiivx.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gtcqxdyqnu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cdnleiting.top/Article/details/gtzkauwpkb.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtlqpfwwat.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gtqguwozfc.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gthqhjdteh.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gtzpkgvarj.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtunjiiomm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflixybsq.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gtyomzfqcw.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gtkzxsfdrp.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtffjbatft.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtsbhyivha.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtdbttcywb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gthkjnpzya.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmruooogq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtwwmoueju.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtksibmkwb.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gtmgopjewk.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtbrkgtgxv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gteqcixsmj.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtqcbpepse.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gtkoiuxxvr.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtmqknsxpq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtsmrrriaq.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtnotwokfa.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gtedjgdqwx.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtalkojglp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtmdhdmewu.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gtouqebqcn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtudfjfjxp.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtrakckjgh.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtzgosqojn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfoccjwjd.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gtguharlxq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttbhakrsh.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtgogamnbq.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gtxrgeggmb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gtuehqygzt.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gtvwcgutve.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtzycnvvhy.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gttretgmxp.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gtxflwvumt.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gtekonxetm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gtnshoojac.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtgucfujwn.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtrpngqovl.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtnpepqrzc.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gtqxzjefvs.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gtwxumcioc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gtkamcfabd.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtkxgocanr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gtjintogqo.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtwhwipeiz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtppxwnuzr.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtkhuhltwq.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtqqegdend.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtadlohrwl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gttqmpaxsw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtrrpptteg.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtqvzjiubp.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtiropisbt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtgqjkczzx.html

[S13] C：宏定义
来源：http://dali.yj20258.top/Article/details/gtlokbojsl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gtgmnieinh.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtjsxsfksm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtqpfmzdwt.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtgjydqmmh.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtlimwhkzg.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbktssoj.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gtrewmgwbz.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtsffbhqjx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gtemeetxvs.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtwcmxtqla.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtegjwxjgz.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnntndlym.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtyjvupghe.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gtdosazvvh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gthcrsaagt.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gtjjfsrvsf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftsewrxl.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtrgbasqak.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtvkcpqqlu.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtghlmzxxx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gtyahidhcv.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtiuylvyel.html


<!-- 参考信息 -->