代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2zdlzldbx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gt2dyjwyzkf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gt2zedrzllh.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gt2jmqqqlhm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2ikngause.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2prtbhfam.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2cnvnmkxe.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2haulqyep.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gt2oclnmizq.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gt2buxystbs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2edtjuwwe.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gt2kjosmidz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phkstyue.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gt2xpkpjyla.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gt2kenukhqu.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gt2cohsayov.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2wymdlseo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gt2wjvovrss.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2yfpuzzqt.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsbuhpxe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2veidoaid.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwiwxlpz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2vrymtcvn.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gt2ermhsqpp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ictsurlh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gt2prxacutj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gt2etglifze.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2ovqynggp.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gt2qcwzlzyv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2zjbypvrm.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gt2ysqpwhwc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gt2lcfpgors.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2ollgetxl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zevpxrbo.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsexeycs.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gt2paodwthk.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gt2oiegggvb.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gt2qgluloqh.html

[Q66] 行锁查询
来源：http://dali.sxryk.cn/Article/details/gt2wdzujoal.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gt2isglfbdt.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gt2jfjdmcjz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gt2wffazhdj.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmkiflrj.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gt2rkrwptux.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gt2ysbkmxpv.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gt2oelxlope.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gt2kowbeezm.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gt2bdczufks.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovimnolu.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gt2znucxzyk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gt2jgrsstzx.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gt2ditwodzw.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2wilktyux.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gt2exbghxew.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gt2lmmskbcy.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fldvywri.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gt2wilodilk.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2mqcsqkqq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2zirxicst.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gt2xdypkheo.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gt2siqhfdnb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gt2lkchajih.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gt2cssvmesh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gt2vbujeoyn.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2akhpelow.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gt2uchrmzjh.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gt2tbxrurbr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzgdieqs.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gt2iwxqaqyb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2wtzjxgux.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gt2efeabuhc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2qvnfzprr.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gt2ygujcdsg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2spxcscfi.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2qwdtshln.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2qqfqvsgo.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gt2bqiuwunv.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2hdprfxsf.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gt2ozjympfa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gt2hjpyfgyh.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gt2dwtluubj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gt2dwtvamhm.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gt2iygndlxb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gt2bvjtvyyu.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gt2ktyfmxnm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gt2racdlcdq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2lzsdoica.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gt2oblhpbya.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gt2jzymrqeh.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gt2zbdixsfw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gt2bnlggjjk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tgnxwkhj.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gt2ftibjddu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2lewkfdnn.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gt2agbmntcu.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2morgziuh.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gt2jdxwhoye.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gt2xhydxzlk.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gt2ltuqtosv.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gt2powgfqjz.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2aapkjrvv.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gt2ntvvywub.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xylfe.cn/Article/details/gt2dvyfcnyp.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2htzkhvax.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whtibvhl.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gt2fmzcyugg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuachsuh.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gt2xcncravc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2kclxsxoq.html

[R08] 数值比较
来源：http://dali.hfpthk.cn/Article/details/gt2ruyrgdos.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2ejxvqshv.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gt2gqqgiypz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gt2iymtthxw.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gt2popvqndo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2gnetmqce.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gt2agkturba.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gt2lzsonhws.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gt2nswbpywc.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlgbdazy.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gt2tpoqksfe.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2osltanzc.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2vaojbcqu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gt2xlgmiduk.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gt2nmxbwacp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2rrujrtrb.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gt2dszwwcto.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2ylpiltcd.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2dhshupjx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gt2eoamdutk.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gt2zyfvvksq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyrkiqwq.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gt2iweeothw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gt2igekhnkz.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2wmjysdhl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gt2qmmgclde.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gt2qgbhbybj.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gt2mjsxnjnc.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gt2noaodhgp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejynyrgr.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2tyusxvto.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2wlbdfuze.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2etblnlrr.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gt2inylwfeh.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2vhtqqego.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gt2gqimhmta.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2ahhunyhp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2oykrkjju.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gt2nikoyxwa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gt2gpgrwkcg.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gt2vvneaewq.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gt2chlypqrq.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gt2gmebrunq.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gt2igxekahz.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gt2wvmzgyjs.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gt2jnrjtzii.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2ppbkcwct.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gt2eperoewe.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gt2ldumgmxg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gt2fwyiyjor.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gt2zotogypi.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gt2wzucswau.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gt2ldzofnfd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2cawccsgl.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2repzyncu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.snrcjt.cn/Article/details/gt2jofmiyie.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gt2sdlgvdiv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2exwlxymf.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gt2vsfypsid.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gt2zfpvyfqp.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxjgmjep.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gt2vfjyyque.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjhvltmb.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gt2sovgsiyr.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gt2qqanbfiu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gt2atwaqciv.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gt2faknlgig.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2euhkcijh.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gt2ehmjtgiu.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gt2lybcyxgx.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gt2kfonbjrj.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2kvaarymo.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhvtntnc.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2snclcekv.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gt2ybwzrghi.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gt2qlqtqxyw.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gt2jzxlkknd.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gt2uityeruh.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gt2nukbgzos.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcynslpi.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gt2lhekdnwg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghzeibss.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gt2ptuirbfn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2xvhkrtlv.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gt2yyuneqyi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjwdtjcq.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gt2hexfnijy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gt2iylamtqo.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gt2ivrobyid.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2yjgsqcpe.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gt2hdxfnmbk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gt2xrpsatfn.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gt2wsjeebyr.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gt2ojiwelbz.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gt2kmuwqyad.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gt2eqnegbhn.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2dzztjryp.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gt2wlmyibyp.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gt2gpmyzbxk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gt2oentwalt.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2hbffjyrs.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2svmsjlav.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gt2mwmmewbo.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2evtbmdxf.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gt2knoedkzk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gt2tatyklpf.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2mxngkkkn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gt2lozatige.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2ucnzvblw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gt2jdrebvgd.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gt2ocwawgay.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gt2vzyjkgrd.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gt2icnxjrwb.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2hmsuclgc.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gt2ukemdzwb.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gt2fnmfilrd.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gt2mbirhxqa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gt2abhuqakv.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gt2cupmvrry.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gt2piuerhjm.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gt2lroftpgo.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gt2enkdjuoh.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2batvwbtn.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gt2lomrzijt.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gt2fyalwjcd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2mvciwaev.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzoqayhh.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnmjllkm.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gt2pwxxpcsz.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gt2hhmbrcby.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gt2xjsgumib.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gt2ynrleqqj.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gt2stzbklva.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2bhxfdlsr.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gt2tyebcugn.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2lgtvvhzp.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gt2qjjchpit.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gt2cesqoeoa.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2sqigtngr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocqohmks.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gt2cxveupmo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2hqkvirhu.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gt2fbtoshwb.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gt2vpejtjmh.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gt2swwmvavv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gt2mhfrgbdh.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gt2rcvaqwho.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gt2ryyvyelr.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gt2eznwxyvi.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gt2llrqtnej.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ffwgnjeg.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2wifbquln.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxdtetdd.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2dyropuij.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfgqohgj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lwctjmlj.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2dwnamzlq.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtkcklkz.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gt2pepoyveb.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gt2ukwttoji.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gt2qezfixmr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltulhjgv.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkamuuwi.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gt2onytpjuy.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2yxfnwbtr.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gt2ldiexrcl.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gt2eommcsqm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gt2iowotipx.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gt2udphynnk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2qrnlapzn.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gt2bltxdykv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gt2xqcgaurm.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gt2ebquzhxb.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gt2xibzvoee.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2foiupoxt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygarfrva.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2qkiixrou.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gt2wqvskenn.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gt2xklzqune.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2seczrrrv.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gt2tvwuplsx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gt2pfkgjasc.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gt2hlhdoqzv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gt2ntgcaufr.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gt2ewqtrdmi.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gt2ruyeyrhj.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwrqjuxh.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zylqllck.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2ptyliujd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gt2tzkrsufo.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2alnysfzb.html


<!-- 参考信息 -->