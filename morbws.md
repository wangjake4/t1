代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gt2ukrfgdhv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2wnxpumzq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2taqhonpp.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gt2pfjzngoh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2idweckow.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gt2ibmiklho.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cidiyepz.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gt2tiwnmsqi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2rnghytbz.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gt2gereerhw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gt2yadzvnio.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2wfmgurvh.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gt2ldntjzdv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2yhitnkbi.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gt2pbctclwi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2rpwbvnyy.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehmcdbnr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gt2dqbnskjp.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gt2tsyqhkus.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gt2jxjbjxjh.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gt2lccpudsr.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gt2wmkcemop.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gt2eamzrofk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gt2ylpvlqeb.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gt2ykovydvm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gt2rvsubusm.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gt2kahlsqoo.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gt2zyctcgvh.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gt2lvldajjq.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gt2qqrzuzcw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gt2tivfoitb.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gt2xqaybxkw.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gt2hzaekvoe.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2vtuenord.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gt2vvmpmkbx.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gt2ezqtjnyu.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2rqxjesqs.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gt2mpfwmymu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2bypcnfbg.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gt2hgxmawvz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gt2eruvnxdx.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2egtvayar.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2mmpzoeyo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gt2jaarmmsv.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gt2tiyphpix.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gt2hkdygjas.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtxoymjt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gt2extvdyoe.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gt2gdjhvwgb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gt2cyfvxqxi.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2lkmckidv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gt2mxpjsozm.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gt2zbrpbqgx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2hsvbvzts.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gt2ybcdeizz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2iulnqbna.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2fivsassp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2cvgzimke.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2tmvptqur.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2xxhhzeon.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gt2nfebvztb.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2fbyplxnl.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gt2phtkrrtb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gt2ngthafsl.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gt2bqwdaeox.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gt2jetdsvfe.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2gozqbquk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gt2sorzkjyl.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gt2asikqlij.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gt2pimfruoe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2vcunvhug.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2saxuhjjv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gt2xzccvxos.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxzckkbd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gt2tqrvqqyx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2igyfhlxz.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gt2xbmdbrgx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2kjbspfgw.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gt2tuppwrvm.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gt2icghcisq.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gt2wqbwfgym.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuundniw.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmquhryi.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gt2eqeqfurj.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gt2ycbfikkf.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gt2zcyjmjlc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gt2uhfkbzmw.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gt2aubosiiz.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gt2hcbpmtls.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2zbbafmis.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gt2eniuqaeh.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zacgbecd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gt2hqzzhcbq.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itxnqsej.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gt2zdmefuws.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2okcechbm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gt2cuefrwnk.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gt2hxjvwvct.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2acvcvknj.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gt2tmqnpgmh.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gt2ynfrpeiw.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gt2oanpllax.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2ccrwkcxg.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2pjgczmhf.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gt2ihqntxsw.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gt2vfvmecpp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvatvtjc.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2bqoevgmo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2hmnznxyv.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrzgloih.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjlqwmer.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2cikzqhto.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gt2kzbmlvsr.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdmcjcdn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjdfmovk.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gt2pubfsvmd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gt2uiktspvt.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gt2dwowuudz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gt2klrchrqp.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2lgmgmabd.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2njzdousm.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gt2aaqmrgrn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2dzemsvrb.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gt2naqbniqc.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gt2uqxfmakg.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gt2vgqsqxbb.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gt2ojwiedxw.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unhvinuj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gt2hzwtibvg.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkijgiuc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gt2ikfhfvra.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwqjqpip.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gt2vjetmjnr.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gt2xhadjaiy.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gt2syczayoe.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gt2azcvwhpy.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gt2tcegqhoj.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gt2ttuydaiw.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocxjtfqb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewglsajc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tanke756.top/Article/details/gt2rfcjtvuj.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gt2xliektvr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gt2sspbdpal.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2exzrnyza.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqzdvlls.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gt2iosgziec.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2ybekctbn.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gt2bwjleksm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgpmpfws.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gt2vpoxphfl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2mmtderhf.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gt2tfsivtkb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gt2qdqsfmlv.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gt2sjvhlvdx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gt2dvjgtdlb.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upeenbcv.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gt2qusgwgux.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2jkxzrese.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gt2kujsuypm.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gt2sojesmbd.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2kzbemfhf.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gt2qwuvsltf.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gt2iijjqcms.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gt2egqqlcbv.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2foytobcz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfghkwp.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gt2pjckiwit.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gt2vzzqyuue.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gt2zbkyczwj.html

[R44] 按修改时间查找
来源：http://dali.yonumen.top/Article/details/gt2pahzumwr.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gt2ojnhzhkx.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gt2cakdhqpj.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gt2nmczpnkz.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gt2qmxskfkt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gt2uforoptd.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2gaxqddrg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncepqthd.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gt2gblavyfm.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2qhlpeaet.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gt2mqvoynsl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhoulong.xyz/Article/details/gt2lcagwmax.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gt2clhyedve.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2rgtssclw.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gt2hhfjzahz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gt2kpccxmof.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gt2gjbedqlv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfvshwn.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gt2rmjlkebf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gt2hddsmntq.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gt2qoavvhvb.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtxiawtm.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gt2tahmvyez.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gt2nkfdglts.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2kogarzqz.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gt2htrqmexz.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfdjkgab.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gt2eajfbfia.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gt2psoekidk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2xaskdlua.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2wthczrls.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gt2ftjaioyq.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2awqfnzxk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gt2ztiehxza.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gt2chpmeksy.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gt2coralewe.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2aqmbpzjg.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gt2lyzzzner.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gt2klwwljyt.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gt2iozmnpqp.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2qhqazdvv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gt2thotvcxp.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gt2ebgptlia.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gt2tfkbyggh.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gt2ofthdtfz.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gt2fxfexvae.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gt2kvaxbavt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2urwpfcrp.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gt2bkwgbvpl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2argscmex.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gt2alkfqdvp.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gt2szhpeyuj.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gt2fowtopos.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gt2pumjjxco.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2xohvwlfi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gt2dnwfxetq.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gt2fwfgeptl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gt2frsldupx.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gt2gpyohhqk.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gt2oahdqtvg.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gt2aagxacmg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2ptpugvni.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2epzyfjge.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gt2brolcptl.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gt2yxwwamsa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gt2btaeggqq.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gt2wffkaehl.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gt2hnqndgve.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gt2nbygsccn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gt2cpwjnvip.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2ytohavkb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gt2kwzyeqru.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gt2hcdsnzjl.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gt2ofyxyeyg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dqbojuur.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gt2ltlqbvlr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2nrdeghvy.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gt2wneeimus.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odklcmah.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gt2plegsrjz.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2womyfrts.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gt2pnlsuzrr.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrefestc.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gt2dydaazqk.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gt2osizzfcy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gt2zoimboms.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjzefnwr.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ejwpmuqv.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2sjtudsmy.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gt2jowechlk.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gt2dmrnuslg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gt2hxsfczzc.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gt2cshormxo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gt2ijexmtvs.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gt2osgoefge.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asjicuas.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gt2dimlcche.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gt2pianczyl.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2juyhrttn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gt2gakaxbzj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gt2xmvvvakl.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2jkvkwlcu.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gt2xyjphplq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2vhddvwtp.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyucmwwx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2qahoutpf.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gt2mpbgekvy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwqemslp.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2cgoxobtc.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gt2cjbximds.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2pxtwuxhy.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gt2mrlqzcal.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2fbxqsxcu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrhvzvuv.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gt2fxshvkui.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gt2bblzapsu.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gt2gvlvcgwe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2fdnrnkjw.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gt2ypbyczrc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2hmtwgixf.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gt2hjmgvwth.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gt2gdyalwlm.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gt2nwypjvgw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gt2nqbxlfzc.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvutuowz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gt2mwqifgfk.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gt2oapqsjwp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gt2kovivgsp.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gt2qfpjnjmt.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gt2jyqbpivc.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gt2nsjqbgfx.html


<!-- 参考信息 -->