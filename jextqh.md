代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2nsqeidxr.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gt2yzugrxml.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2kpjlayxy.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gt2dokddovc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2yfkarmab.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gt2myjrqetd.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gt2zlfpwero.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2zxomyncf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2noczkzmn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gt2modttxoo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gt2jxrqvzph.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yevjkjlw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsgsumi.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gt2sfhvwtgd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2pmvafdxx.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gt2nnnrpuhw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2veqiftab.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gt2dcemiwvd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gt2emhlkuiq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2yhsncaom.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gt2gwcwflts.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2lslomvzz.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gt2orzgxlpz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffxpmjyk.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgnyjeux.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tocqkluw.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gt2cepsaksj.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gt2exmjmwyp.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gt2njbmmpli.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dljuoijk.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gt2tbbxihhd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gt2rqrdnkcu.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gt2ibcmusbb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gt2exsnroqz.html

[Q68] 保存点
来源：http://dali.hnxiangtu.top/Article/details/gt2uqefiyqe.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2drzbrdoi.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2hmlbfdmo.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gt2ggerupkh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gt2wklnmzcd.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gt2qnvlztfd.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vljusmce.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gt2eltnljzn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gt2quiqfrvs.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gt2vmpllubr.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gt2xbevbepg.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gt2ylhjpbqg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gt2pzglfjmm.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iapcamjd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gt2ouqzabhc.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2ksvraabn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2rxpvcqbb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fengsongda.top/Article/details/gt2askzzxqc.html

[Q76] 按天统计
来源：http://dali.yuanzhike.top/Article/details/gt2cuivtfpg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtgiadcs.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gt2olcryooj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gt2zcwslaea.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtqkejaw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gaohongyu789.top/Article/details/gt2bmzqolzp.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gt2doizkgqm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htzmyasu.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkhxoccp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2kdaasrgj.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2hzkpmobw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovzvgpxn.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gt2trpycuzn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2ruagcdhr.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2hxspgiry.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2uqnumahi.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gt2tqzxpwyn.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2lmbtkmnn.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gt2xnfjjtox.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gt2fccwiyja.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gt2eibfahyr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gt2chglnfjp.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gt2cbvkirqq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gt2zupcmxxr.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gt2fqvchukc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gt2evbtulbk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gt2vrcjrbas.html

[Q89] 判断表是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofzuvesa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gt2qhsxgqii.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gt2enaalsaa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gt2kdmnvtqp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2vatzlaeq.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gt2mupcgtkm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ahycbgrs.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gt2maxbeori.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gt2ijslgidq.html

set -euo pipefail
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umcssxny.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gt2qopggqke.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smxvzjca.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gt2npcpvpvl.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gt2nzmjlbtp.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yibnytjq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gt2dppvqqdo.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gt2xgeubvgy.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2llulvvgo.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gt2kbbdbyof.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wprkoofi.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syzgvqkv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2sshlcwcv.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gt2vcmesmwg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gt2ajlydwjq.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2bpbpudbb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2aueejodb.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gt2blwvcgrj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gt2qfepxbub.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gt2ucjrklma.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gt2ynvvuqjp.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2yljhqhvd.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2srqkjqcj.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2hnptrzpu.html

esac
来源：http://dali.sweek.top/Article/details/gt2hsnulimm.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gt2hibgcgyc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gt2vzlwzogf.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gt2pjrgdrdo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2mvuidtzm.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gt2irdqcmer.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2ftphtfxp.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2bdmjnrai.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gt2ekcepnxy.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gt2etfctahw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gt2mziowymd.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gt2zucyidov.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gt2wbqbkadz.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gt2ocnsyuif.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnvymwdn.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2lvcywbfm.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gt2whubozes.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gt2ujcwwonc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxnklryg.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2aiyczzif.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gt2giiiymhn.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2wgswierc.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gt2lizqpogq.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2xxlcfaxf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gt2bouubejg.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2vpxgtcea.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2otstaizy.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gt2bsownzjb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gt2awbyrxot.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gt2frbjlcwy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gt2ghhntwtw.html

[R27] 算术展开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agrishsz.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2kizlspno.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gt2drregwnp.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gt2algsgrib.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2hkbxbtsq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gt2ujjiqvfb.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gt2bbfjrjdx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtiquyhc.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gt2yhkwzcwu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mnbmlzzd.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gt2saosvehf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2tzqntiuf.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gt2mfzlkqgv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2qqginuqb.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gt2pwwyjecl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2ywgrkvge.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gt2karbaqog.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gt2unrfpujc.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gt2zpdnsuxg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2oyvfstoh.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2ceqtudtn.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gt2yuytdjad.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gt2gbagrxix.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gt2fquawuta.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gt2ctobwdgw.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2uaizzwxt.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gt2xdgvevhw.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gt2orxoymad.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gt2arofrtto.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtdywsav.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gt2ioammkli.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gt2ddqdwjjb.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gt2yrojntjk.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gt2jafovzys.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gt2jxgdeyro.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gt2pxhjqmtp.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2zdsbtucq.html

find . -name "*.tmp" -delete
来源：http://dali.jqgfzy.top/Article/details/gt2yjuzojao.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2dmxsswjk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrqcqlco.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2akhtgxaa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2ihpslpdz.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gt2qvjtcctd.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jveurpqk.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gt2yyegiafn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gt2dfcbpwbc.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gt2gueqkhgk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2wfnzbypc.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gt2dkiqitdq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gt2ctuaexqq.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2qodtipkv.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gt2hlehdarq.html

[R53] 查看文件头与实时尾
来源：http://dali.ybcxt.top/Article/details/gt2rnvudffn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gt2sssipqzf.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gt2mwghlipv.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gt2tybpqmld.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gt2xaoyhmww.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdcjkjrx.html

[R56] 远程拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2lnlslanp.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryyvzffs.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gt2wddibzth.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gt2mifcskqh.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2swmzcmbe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2bupcbmun.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2sluqpnca.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gt2jyywbswe.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2qkkacktf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gt2zxpiutjr.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stboiahs.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gt2kczwygdg.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gt2uuzypmdc.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gt2nqztayuh.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avgamprs.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csoxieit.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gt2kfemozuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gt2emfwkokl.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gt2sedjaikp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gt2crsqssrb.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gt2tcpmcoug.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2belrwoic.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gt2iiekaxmu.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gt2phfifaez.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gt2vnmptpyq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gt2eqizzctk.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gt2pyhesvhi.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2kcjegorz.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gt2wtlbvfrz.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gt2pliajhkl.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2cpqjwawi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gt2hhfhvrbo.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gt2pomvgmwk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gt2rerjdapg.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gt2laiewcst.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjhwgszv.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gt2tvcabbey.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gt2xqgpjfbv.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2ofvjbmli.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gt2qhhkkdvr.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gt2fzdytfaa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gt2bwvefhgo.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gt2fcyzbetf.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2emzruahy.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gt2kpgojviv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gt2ctjtfwye.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gt2knovijcb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gt2ebzahymt.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gt2ungsicdu.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gt2zpoxzwqe.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2znroljbi.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlecixgj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2uezltzqj.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2dwkwgvms.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gt2nmgwksdj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gt2dymdzlpc.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2rqgsvwfm.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gt2ieexpvfu.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gt2rsrqjcvv.html

int x; scanf("%d", &x);
来源：http://dali.zdqjudy.top/Article/details/gt2vzmslefv.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gt2yarukcio.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjwrvitm.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2tvkzyvrx.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbygqdvt.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2nckjxkav.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gt2bdaininy.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gt2czfvqeoa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gt2abcgumuo.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gt2rlbbwigt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gt2rmfdoguc.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gt2zdibifov.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gt2yagofxyq.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gt2rivgliry.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fymmlzaf.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2hpsefzic.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gt2qiuzlcpp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gt2svohjkvt.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2ndauoxox.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gt2auysyzml.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gt2lkrgfpwn.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gt2nxtajwjw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gt2dknjrord.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gt2akqsohct.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gt2fmkunibc.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2kbherczi.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gt2fcenjpkm.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gt2oktxinei.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gt2vjkywksk.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2rmlckqjy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gt2auqxcqoi.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gt2egyatolv.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vytyuhfu.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gt2exbbxhnv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2mtpxtfrw.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwtkavxj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2jmamctei.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gt2ycqugfbo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gt2smknvbqw.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2iuouvelc.html


<!-- 参考信息 -->