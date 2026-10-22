代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gt2axyhykhl.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gt2zkkoztwe.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gt2upqfytco.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgpjxzfd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gt2fpxbvtrz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gt2kwypfyfz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gt2twftygpc.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zknhzhyl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2bkirepki.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2titkhnlo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycicrymq.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gt2mghypbpn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2gibfavjh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gt2wrjtcdma.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gt2rqeybofc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2liibhpao.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gt2bhdfclws.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2ydhcpnmc.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gt2zupzobfu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2zwlujifj.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gt2lkrrgqqe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gt2dhldcxgm.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gt2vtfmxloj.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gt2kvcjfvjw.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gt2bhwqzcrl.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gt2cqzctlax.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2tezuytun.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gt2eysawfwr.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gt2qclrlcsq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2sfomelix.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gt2slakaqfp.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gt2eixtvrfk.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2hppuihzv.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2qbgiiipu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gt2oqkinctt.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gt2rgvlkcsn.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gt2jeuamdhg.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gt2jcvgkozq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gt2pqshlccr.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gt2nfaesasv.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhugfvnv.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2hcgscdja.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2wxazoykf.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gt2tfmbouqk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gt2yndebans.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2msqrzehe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2dnnhtsud.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmjfjmjh.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gt2gypszdhk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyfuvnkq.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysaqtodz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gt2iqtebojd.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gt2hckjjjmt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gt2tyvpqvps.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gt2oecftfrn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gt2yvmoyacy.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gt2mbebgbcx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2eazefcvn.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2uvldtjlk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vznihszj.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2niaarljm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2nicqvcxr.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2ktftcird.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2aqbakzif.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gt2cwnypxgh.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2gfiujlac.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gt2dzomwpxu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gt2riimiyho.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gt2whengavw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2rxiowxxl.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gt2qrndkfee.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gt2befzjgoh.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2gjmayskm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gt2vemisits.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2nsmbvixg.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2wixzcrkp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gt2kqtpbzzn.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gt2athtcesg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptbqvsgp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2svcozuep.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gt2psprmarb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jugulybe.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2xluobdie.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gt2cddqigzy.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqtxodrt.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gt2cbetiujm.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gt2ibdmught.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gt2mkpdwxtv.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gt2ioybvpqx.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2ngeaqjqo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gt2mpqpgaux.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2hhtmxgyo.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gt2kxypjlri.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2awmcllig.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gt2degsbjbu.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gt2leksuwqu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gt2knubbadp.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gt2oqiqwyki.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gt2dvsmoewk.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2fdksoklo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2bljcivzy.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2rakqkwgd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2yerldxuz.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gt2obserfpy.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gt2uvwiywae.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gt2ergquxkf.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2auljwfyh.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2bdnegxgv.html

esac
来源：http://dali.yj20258888.top/Article/details/gt2xluthplt.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2jxoipyaz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gt2ytgbxonq.html

[R13] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gt2bjmaorur.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gt2yacsjkfa.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gt2hhqqzvvg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2wjxoxvsh.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2nmlyzpgd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gt2wajkctsc.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gt2wmyinvlb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2qrjgzpnr.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gt2nwhisxsd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvlisjuo.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gt2shbnkxle.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gt2tmaxkqns.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utjatxuz.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gt2cnpazktu.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gt2lgspmnrm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gt2lukjamsd.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2jevsvgxq.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gt2xusfhlzi.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gt2fpqlqdhw.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdvzguam.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycbijgsg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gt2jqbupdvg.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2utzpqkgh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2xqqybvhh.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gt2qqojwvxy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gt2jnnpbhcj.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gt2ctnxghik.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gt2lmjdijvp.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gt2bakzoxol.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gt2btvtgxkp.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gt2yeocszjp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pxogzrnp.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gt2hkqhzqrx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gt2uhzpswqq.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gt2koxpeedx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gt2giqijxbw.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2ffqujuwo.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qacgpupl.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gt2zvegqqtt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obmwgcuy.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gt2tdcoawui.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gt2iajqxrjd.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gt2wflfvljm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2keujjepi.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehtcufzq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gt2oitckxpb.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gt2hbhmptdk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gt2rwfuuaga.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gt2ylqbebgi.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gt2uljeldmk.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggqhwmvo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plbvdbqv.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gt2gqhyvqxx.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2xmczpdvh.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gt2qayzvrxw.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gt2bqegzogp.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gt2xqfouwje.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2ompmrrmu.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2bpahxtkm.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2zcowospg.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gt2goooziyl.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2qmolqxwl.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whynunyn.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gt2umybiilp.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gt2sbicsnfy.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gt2eaottggr.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gt2rewchkyl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gt2mravvmtm.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2gijdnlqe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gt2rykkrwba.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gt2yrnpwbrh.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2pelxuvru.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnzujbse.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gt2knbjgzai.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gt2uiborzes.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2tlavoyow.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gt2vyswyfpn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gt2dxhodxbu.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gt2cpxrnnui.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhbymmjy.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gt2xpeeiotj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gt2lacmhakh.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gt2mkqpgroq.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwcldwrd.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gt2qsszwnlo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsvnlidw.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gt2lftltbac.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2fyeajmzu.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2zvlbcoaf.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2iyquxlhs.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gt2wwcgxqqn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gt2ernqiwnl.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2zvglqdlv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gt2dnqddeyr.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwqpafdk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gt2cztivmnu.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wihhxkfg.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gt2eyzuztaq.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gt2ztqhxasx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvrsfeb.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gt2kmvpnyhi.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkjzbfdk.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygjskwuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gt2ogtouior.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gt2zcommskc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gt2icelbtky.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gt2ntaywgge.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2bveiohsh.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gt2fhedrleq.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gt2evfcrrhg.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gt2jpzerizk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2jmpmrvbn.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2cyxbabgh.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2bghenyjz.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gt2cbytnjhd.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfvdijuo.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2rosbztez.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gt2cxwlldyt.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gt2gdipfrmu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjynhaqf.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gt2rcqttbuq.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doxradnq.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gt2vtsrttvq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gt2kbjwdsrt.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2cvrimsja.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gt2mlhuyrxs.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gt2npaxlwoy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gt2qbknyasj.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2dyxhjfxj.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gt2eijxovvf.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gt2iciurfpr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2volloajh.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2dvxqgscd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cqqwz.cn/Article/details/gt2muiuebxk.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gt2dozqwehk.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gt2ybarkqss.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bqqdtjvk.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpunrqie.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2jygsdxpp.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvtnireg.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gt2cazrgulf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gt2tbksdoqa.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gt2qebblbsf.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gt2ncojgvvl.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gt2jdwlhmwk.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gt2ddtknchi.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gt2ebuptdcu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gt2lhowahct.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2huyroztx.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gt2lksgknwy.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2cxypgxai.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gt2coviejfb.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gt2loxokzma.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gt2nyffnqpz.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gt2egzjdvdq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2hpikjtib.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gt2mnqzsqnz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gt2zpgqurtu.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gt2dreqlhfx.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gt2txwdgtxg.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2zghdmpmz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gt2ssankwor.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2hirghlcn.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2suquoiag.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gt2qxvvxmcn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuiarxmn.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gt2osmposwz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gt2ymgksqiv.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gt2fvouxqal.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2xlyfrbwu.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gt2ansnpzfw.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gt2rjzduoik.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gt2yvoqdbgh.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gt2xjysownl.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2scylkbrn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igelssqb.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2rzknbqvm.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gt2yedwhvmq.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gt2lvwulvsw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gt2tbfesbow.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gt2ageavqyd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxempzga.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gt2bthppjzi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gt2uwkuhvnr.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2eeodgocs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gt2iokelcgq.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gt2rizrpuyc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gt2ppmwzbfq.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gt2fjlxjsxl.html


<!-- 参考信息 -->