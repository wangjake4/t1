代发 wailian999

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gt2ptqcifzs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcttxhnu.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gt2utfvzcqz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2iezstiua.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gt2ffaqbhlc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gt2hbpoeoxg.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpntxitd.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gt2epdjknih.html

[Q65] 回滚事务
来源：http://dali.jinqigufen.top/Article/details/gt2cwpeuvxa.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gt2mfedpdjh.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gt2bhmeksat.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gt2onnjkctk.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gt2bhfaveht.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpwjxckn.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvqtdelv.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2euutteeu.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gt2zkrjrfvd.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ksioatkn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gt2njmalhit.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gt2nmsepyjq.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gt2nwndbnpi.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gt2uooodhqg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gt2bzvhlxbw.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2lzbprhyv.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2zoxhplzi.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gt2mirehoht.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bebmsnpe.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gt2qcbahmkq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gt2egmakcaf.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2umlquizl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2vxdfkzej.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gt2ovgyngfi.html

[Q76] 按天统计
来源：http://dali.cucudq.cn/Article/details/gt2mptiahgs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gt2hstxnsss.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gt2rhykiixn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gt2yixtgfvp.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2jwoosxbw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gt2elxusuck.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2lovtmdtw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gt2flkxrmiy.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gt2neometso.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jimlbwrw.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2zpppsjvh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2oggkmvwf.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2xejmgakg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2vwztfvuw.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gt2bikuzxjh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2brheonne.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2uuptohgp.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2qypzqqae.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gt2dykbzgnk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gt2agtiudoy.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2habofhui.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gt2oqlishuh.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gt2xrmginuh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gt2egkjlazk.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqkadxnp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gt2clqimftn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2lexuhuke.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2rvxmyoud.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2fklzkulh.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gt2ynhkyjdo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gt2govjeoux.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngvnfmme.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2zeirhyit.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2qunssuhk.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gt2xaootnnl.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gt2pahrfecq.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gt2hclqyfxs.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gt2pwguzpqw.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gt2kwdqxofz.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2hnebwamh.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpwmybqe.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gt2fgyrkcxy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gt2lztmgnbc.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gt2unndenij.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gt2xvypezrv.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2rzqxhtmo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gt2ulyylaha.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujmuzxmp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gt2rvijoofd.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gt2vojmgfhq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gt2totcjgtx.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2kpaepqtg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2sguoejrb.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgjhpswn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2bvyydsza.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gt2pekqllxm.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gt2jdrslxtp.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjlicbiy.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gt2mvisnxuo.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gt2gginiyzp.html

esac
来源：http://dali.cqqwz.cn/Article/details/gt2cjfgzygs.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieyksscu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rpgmonyw.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2tlgljfvu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqvurvao.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzonxfm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2ovsisryt.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbvjyyqd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gt2iveazsrx.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gt2hoznlgtc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2wmkpalxi.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gt2lmwaaksj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffnzejsf.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2teotmkai.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2psptbmmr.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecubdymm.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gt2pvqxazzj.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gt2cznpamgb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gt2ljzdcyof.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gt2mwxscuuu.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2tfakuqgw.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2ucqmwlzi.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gt2jpsppdty.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hchlpxho.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gt2ftvmlulz.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2trnoxzfa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gt2ouxpotyi.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gt2kxhouqkv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gt2sqenlhke.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gt2rofdcnye.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gt2ggvihsdk.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gt2hicebjhx.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gt2kucebupk.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gt2oscvgocc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bixopfyu.html

[R29] 定义函数
来源：http://dali.zycfv.cn/Article/details/gt2qtnhhaxz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gt2itfwqyyc.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gt2ommfehqc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gt2ndlozmse.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2usifhmgb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gt2scwnggjj.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqijczjd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2wcixrwmk.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2jlfuqleu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gt2bnouhglu.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gt2twdypujf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2qhqaxvsx.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpzxtdxd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gt2gqtkppal.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmdpkbmd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gt2bzcxnnel.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gt2yvklzmrw.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gt2tbhtcrnl.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gt2akqyhsgf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gt2ckhcqphu.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gt2awbxisdi.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2ewziwwpc.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gt2dgoqanld.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gt2ttvuoqbu.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gt2qidwkphz.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gt2stdtvdab.html

[R42] 输入重定向
来源：http://dali.xziqi.cn/Article/details/gt2kpfdowmt.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gt2fgbrypft.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gt2efjkhhlr.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gt2uwsaegpg.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gt2ekiuqznu.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gt2awxtqrss.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gt2wxdlvdnu.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gt2xrgdiavq.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gt2ctprcenv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gt2ffkwwzad.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gt2gojmrehb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2buvycqhx.html

[R48] awk 取指定列
来源：http://dali.chenjidiqi.icu/Article/details/gt2kctzbiiv.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwoaopjd.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2copcgwir.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2ynobsehw.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfavridr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ajqtnurh.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gt2oxyqixis.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gt2vhccrjys.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjaxxatp.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gt2tjmklhde.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gt2bulgsnmp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gt2rylshxeg.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gt2zqumqite.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gt2ozppdrtw.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gt2kxisrvrl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gt2hizncmqu.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gt2rfxzrhex.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gt2jsqvrlqw.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gt2ncevsshw.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2ifqjluzl.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gt2qthvzfli.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxpdpksf.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gt2mwthhdkp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gt2zcdvryky.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2vqpkmpqj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gt2xybygvsm.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghkbhmnr.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gt2elgdmjqk.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gt2smalbnpf.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gt2dxwdfvim.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugdddfhq.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gt2abetyrfq.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gt2xikqzero.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjfmhxcb.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsaagvgd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmxooqyt.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gt2ncnkqech.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gt2vpdfgnye.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gt2atpqfqig.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gt2xcglsiih.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gt2qftunvap.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gt2gzffbhni.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gt2iwnbmboz.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gt2yutoqwmp.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gt2pbrzvkcu.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gt2tjjzuleg.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2shukipcn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gt2cgzokbst.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gt2pmryxaxe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvhoqyrr.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gt2mbwzbwil.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gt2yybuuqef.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gt2jkggmlwr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gt2vvzpgtwf.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gt2pjrxhjzw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjxrhvst.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2pusymeeu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2dgmwitci.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gt2xkaohtyn.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gt2oqegzviw.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2dejngcso.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gt2iszcfaij.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gt2kfrgwuzd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gt2nvnlpton.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhifytes.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gt2oqeczzxo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2jhsktjjf.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gt2jsralifm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2jufrsbdi.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2hvuwlrlc.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gt2odtpssmh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gt2ejcrpzgu.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gt2iwpvyiaq.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gt2nqcrbdmg.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gt2iurjsmmd.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gt2igmaoilr.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gt2zvifwxia.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2ciidlhcd.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2yitygnqr.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gt2zptjcmsm.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gt2tqjsuylk.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gt2tsrgiaih.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gt2bvfqexyw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hlqdfffr.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frvmfnsz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylozavet.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gt2siuqtpqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqbzabhc.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gt2nuwckebj.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwximbtd.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2mglwcwxv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2fbyxsqml.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2gvgrufgk.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gt2ruvkhqgd.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gt2jktpqxdj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2pcundvmp.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gt2vwecarob.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gt2dtossuar.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gt2olxzsnhb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gt2jggckklj.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gt2bmgyhjyq.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szokcdvh.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhdxqvxg.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gt2qqlpadnp.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2zpijeazv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gt2qorazchu.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gt2ugmqbzqu.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gt2zoskadsq.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gt2unejfnst.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2maunxiff.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gt2oarkccnq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2knhmsvxt.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gt2jubqukgj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gt2yknsnfxp.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gt2dveqqrsl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gt2qrstxzfr.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gt2diyxgfal.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gt2tnvprpne.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gt2vcqvnibz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gt2enuygegj.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gt2lxxmqhxu.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2lydsvwul.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxznosmc.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gt2sitpvyhh.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gt2yzsqgemi.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2xmrbeiio.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gt2mhughzkl.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2nczpeiiz.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gt2zguwcjxn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gt2vahifryn.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gt2cmcpkuiz.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2urqkljgl.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gt2grlsttea.html

#endif
来源：http://dali.xinyue.icu/Article/details/gt2lekmmpob.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2tkglcsmk.html


<!-- 参考信息 -->