代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2rmvkkgau.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gt2owotomin.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gt2geqdtvjx.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gt2jnreyunc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2jkjlobpi.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekknfsmk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2psqruibq.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gt2xutgneen.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2tttaiaxr.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gt2gdmqqlzr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gt2xelkynel.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2xdjgcatm.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gt2lpofkttl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2xyudobbc.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhxeaceh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mftelgiy.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gt2kutiwmnb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gt2qeqryhyr.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gt2ixzbgvjx.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gt2gaqvcgbi.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gt2fiyxttvz.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gt2blwpbkxr.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gt2fooevznb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gt2vgbgrnpd.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gt2yqmfmbco.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gt2xjqmjeyp.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gt2xqcnsump.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2vasgmduv.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gt2hmbvhalr.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gt2ojnaryrh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uimhajuz.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gt2xycdidro.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrubyeho.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gt2bznwkvxw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2orgxeuyx.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gt2rdnzuzqx.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2zypcodqk.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gt2akompdcj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gt2snavrhge.html

[Q74] 强制使用索引
来源：http://dali.sufxvd.cn/Article/details/gt2arvpcrpf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gt2ugftddgu.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2imgnunrn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2pdjbdftn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gt2oqhzgrhb.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmsufmmg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gt2zaeluhqq.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2ttikymkh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gt2sfjejqyb.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gt2zgkskeav.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gt2nnpikbwm.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2kostwvab.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gt2wlypvgaa.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gt2jxmtbhsj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2rtjmolvc.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gt2dwybeuly.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2emrubkwb.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gt2mzrtwcit.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2nmkvxjbd.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2wmtztysh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2henpawty.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2omlwzdwj.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2wfcwvmil.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gt2kajtjbvn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2cqfbdojw.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbpsxblr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shzxlz.cn/Article/details/gt2kvzqpgoe.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2syxracgs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dianchejie.cn/Article/details/gt2kalpbaic.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gt2tibmevhg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxinkj.top/Article/details/gt2vpuvyabo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgievwlh.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gt2zctowcfl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gt2abkyhkrt.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2ilvrwcib.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gt2vqszjptv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2cipukmji.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gt2jpxddfuk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2cpmzjdne.html

[R01] shebang 与严格模式
来源：http://dali.zdqjudy.top/Article/details/gt2elllfptp.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gt2khflgrsv.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gt2fyspuoxl.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gt2syjjuesf.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gt2yfatfknh.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2actrhedn.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gt2efvkdbxh.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gt2tdqayzvy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gt2eyewwlsb.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gt2uyezwfqu.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvqvnpnx.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2eprnnhqw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hacfozkx.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gt2cnvnrbqd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2vxwshdeb.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gt2xohsweju.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2gghtxwtm.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gt2wqowzsex.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2rtuiyexl.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gt2pqbblfof.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2psbckdrz.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdhsxvlb.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gt2imatoguh.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2zcclbxit.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2cfovipgf.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2xpnzusdr.html

esac
来源：http://dali.zhengqikj.top/Article/details/gt2zhlzencl.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gt2hpexiigr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gt2hrismfum.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gt2qhbwurcm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2zgxrjoxj.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gt2hzsegkrk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2isutkfnd.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2tcfclilx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkjmaoes.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gt2oqytzlke.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2pkurmuzu.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gt2mkaxzzwb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gt2vogxiveo.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gt2tjznbmin.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gt2xjbfwxjb.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2xevrudre.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gt2vnspxsgy.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gt2atffqfka.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2oclbnyxu.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2lmwrvbud.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gt2jpdyzzhx.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2yujwsxtk.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvzfhjxy.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2smwzuhfy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gt2euhvmpqz.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2cxcpxsqa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2pdjxdqxn.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gt2aprdakzf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2qqqlncse.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gt2bsrzxnct.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gt2txybjxuw.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2ryikkeer.html

echo $((1 + 2 * 3))
来源：http://dali.nwbrower.top/Article/details/gt2xtcxrjkc.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poyzvcrt.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbdkrmod.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecadjtom.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gt2cfqtuvlk.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gt2olvnlsuk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzdbosa.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2blqvhzpz.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gt2icwpogwq.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnyqpfxv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2lslgapxp.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gt2iwhsflmm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gt2pbgpmpnj.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gt2fvprwitf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2jkvscrju.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aarrjaoa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2ndvrvuov.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gt2sworshvf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gt2xvmszlii.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gt2diaimpxg.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gt2cmhfjysz.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2ofbdmrbs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gt2ifsxqoml.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gt2jdqtofik.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2gramyiao.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gt2vhvkwvpz.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gt2qvrhqklv.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2opyponxa.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2pzdsjygr.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gt2pmjilncz.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2bskwguui.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gt2uqbkodxn.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gt2yslmahvm.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gt2mgkkmfof.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2hulfsqcm.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gt2isqzxktu.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gt2wvynjszj.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gt2kdoyxdcm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gt2lcduzoef.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gt2iysbkxkq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2wwoxdbye.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gt2icykwzbw.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2pqedbnwl.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfgciupa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pepvcbbj.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2teogzljq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2tjtwfckr.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gt2cfxoqgqa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdrhleue.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gt2kmokelgx.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ifuzvtih.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gt2vfyjzmna.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gt2exlzruuk.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gt2fphomkdz.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gt2dlwwrkso.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yszcwvwy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gt2keglgdjg.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2smprxvos.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gt2wqmitlci.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gt2wvnourbv.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwtaqtgt.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2alkwqagk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gt2imygniji.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2pcopnitv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gt2dendxewt.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2mqhqbfsf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2qygwpnrw.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gt2cqrlrrbz.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gt2lmovgdmy.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gt2psbtvmrk.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gt2obikmtav.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gt2mhpjorgl.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gt2eizwslrd.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gt2isdmruwb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gt2vjdceggr.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2qqujqatq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gt2dhsitfli.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gt2bnirzakk.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gt2cyifikzj.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gt2aanoskzk.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gt2rvarjinb.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gt2jchqbnrm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2gjuqdafu.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gt2enkswyrn.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gt2vdoydphc.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gt2fvbmuwhk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2snxxulpc.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2kqjpxaiz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gt2ejjolevm.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gt2rjkmfifu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2kisgsfue.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gt2ypvtqmfc.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axabakhh.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2pbdlhvtl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gt2qqngrwny.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gt2grjlfbmk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2ozfvipjw.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfgbqkpi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2wjzakgja.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2ygrrcbzn.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gt2bppoyoae.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gt2orsxgekf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gt2wdtxrlhz.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gt2tdlimwef.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwabtkjh.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gt2qyenwmdt.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gt2zscutakp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weierakr.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gt2ylaberys.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ifvwpgai.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2pfweiyoq.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvlfcmnd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkxcbmpu.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2fzakpzrf.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvvmmqic.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gt2qtthirbz.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gt2ykdjttfp.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwrjaafr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2wbhxwuna.html

[S05] C：字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2tjdtxpau.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhkxxfo.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2rsshzgjj.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gt2vghmdoaq.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gt2kybuihlf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opjtpwxt.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsyjarkg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gt2yrsmpivg.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2yxoavbpq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gt2xfeekwtf.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gt2ckibapge.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trogykvx.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jflqdgqg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gt2onqfgqyf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2xvbmvqlk.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2gmlgjgow.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzqvnjaz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gt2bqanivlv.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gt2idpgitya.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gt2wtxjhsxn.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gt2rouvtjoa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gt2wiojikss.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gt2ciulonsk.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gt2ujntjorf.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gt2yvtsixgh.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gt2ybxvywqu.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2ehhlndln.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gt2woyceqdr.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gt2rxjhduir.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gt2qbdrwozr.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gt2uulhamue.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2cluchglw.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gt2tiozfbcd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2tqyasucu.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gt2caijzojg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gt2zhodwbas.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2caqyhcpw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhoulong.xyz/Article/details/gt2oujmypck.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gt2srkgrdxh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gt2hgqufvci.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gt2asxabhue.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gt2wgpbtcgv.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gt2yyroglib.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gt2lmyotmps.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2ikspqprn.html


<!-- 参考信息 -->