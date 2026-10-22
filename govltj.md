代发 wailian999

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gt2jlqrhkmg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2qbmyqyyp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzhdfyt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2acnremne.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2hukqsyfr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gt2rsufukhe.html

[Q64] 提交事务
来源：http://dali.316326.xyz/Article/details/gt2chqndcus.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gt2dlsypjfy.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gt2zwjapehm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoutqkp.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gt2niggnyut.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gt2ikkwrgfk.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gt2hjbjzrfc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gt2qsxjofdc.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gt2wpnsknsk.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gt2hfqyuhzc.html

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gt2jbdzetcv.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gt2ersjccws.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gt2tttdjggk.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gt2wxiwevth.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gt2fmqkggjc.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gt2jqzdyvst.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gt2pfgnaxpo.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gt2ajuqetbj.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2evkapsno.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gt2uoyrvfwc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egemtxlp.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gt2clirfcpu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gt2yphjeydp.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2tjakgtpm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2nmoqlnhm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gt2njhgiovd.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gt2ttymhquh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gt2awzbnklo.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gt2wymgmclh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gt2gpsrswjb.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gt2dxknlqkb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gt2duwazzfb.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gt2wyhhqdld.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gt2jmufqshd.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gt2gftecwiv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2npwaakll.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2wojfkdzj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2qzpfouoj.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gt2fndofwgj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2zjrwqnkn.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2ivtjquwf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2yaiqnlmb.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gt2ysbemspy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2wzcbhqqa.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gt2limquore.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2feysuriu.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gt2tuhacevv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gt2loltpaey.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gt2lumjpgle.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gt2mbmhgtwi.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gt2pcdyaqan.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gt2ulbgjfbd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2uyhmxrsc.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2hxgjtupe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gt2vpdyqaxa.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gt2tkxwnxij.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2saudtphi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjitnfhy.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gt2qijllxrx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tsztawwh.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gt2unjmviba.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gt2newnleet.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gt2fxrhqula.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gt2abvxwneh.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gt2yppmxvbz.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gt2mqdqqkrc.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gt2iwwiltix.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ukcanfhh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppkyijzo.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gt2hpoaenid.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gt2znzwsngr.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kknmzzjr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uuxjcktm.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gt2iazjroxb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gt2mzfdwgve.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gt2kemdbzfc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gt2fgbqopcz.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2usnjrbjp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gt2nawuruft.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gt2nndxglna.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gt2ifnqbvlo.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gt2dhcahajf.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gt2kgekuqep.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2mgcbbeif.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2wfjrnomb.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gt2uzperdab.html

esac
来源：http://dali.chenlongwang.top/Article/details/gt2qtzyppdq.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2bedltnue.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2oshrxnqd.html

[R13] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gt2rmwozies.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2xzkxaahk.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gt2jpejjzje.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2tbquzohb.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqfojxgs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnfkfqxp.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gt2knxfpgvu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2ehgcfyhf.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gt2volwdkpi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gt2yxuhmguf.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gt2tgluvwwi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gt2mgmumydn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2whfekuxh.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gt2cybfbxhn.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gt2qinkghja.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2snvdyzml.html

[R21] 字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2uopqzwxu.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gt2vkpftrni.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2femhttpl.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gt2qlztqjwh.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2jocpxkis.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gt2debqpmxw.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2anpmltyk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnyrfiiz.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gt2wcurukpr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2aldzcvsn.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gt2xzgzxrdn.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gt2pmkqwysk.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gt2jpxvrttq.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gt2zfergtqx.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gt2bemoejvl.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gt2stuolfjn.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2relskxkg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gt2oafeuwnl.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tunyuyxk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gt2shzsquxn.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gt2uutkevem.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2suwdctgt.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mepbcbhi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2dfiebvfw.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gt2nkwlpzri.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gt2zrupiyme.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gt2xlwfktox.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2mnkwrzio.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gt2iawljtfy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gt2aqvyxonn.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gt2djoardhp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gt2jxrfbwmx.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2mpptaudl.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gt2stqbtbvv.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gt2escysbse.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gt2mdqhomts.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2azozrild.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2tjefxubf.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gt2hgrquhlf.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gt2acfjeaud.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gt2czstwjiq.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtwtwtlh.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gt2rschekjf.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2rhkcjxox.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gt2voqrbrjg.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gt2knvfvati.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gt2ligpqbfr.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gt2ojmcxmdd.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gt2iijddtjy.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrmdgfyb.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gt2zsxewnmv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gt2ywoxjesh.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gt2luhiseyt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2qblogvbb.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gt2fxedtxpq.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgihetli.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcjjnrxk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gt2xiruxznv.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gt2sahohjwj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2gsrjpavn.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gt2rnqtduwa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gt2ifpyegbb.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gt2ixzcsrsi.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2esnowmev.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gt2etiizzhu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gt2dpteopbp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itmhogmh.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gt2vbaslhep.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gt2axslsgdo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gt2hqvuwher.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gt2zqnxvihh.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gt2glvdhftj.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gt2tzfmpsbb.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihjqwpbr.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gt2onoceizo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gt2thnaydtr.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2mrgqvuxw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gt2owxaiyjt.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gt2aalqcoyq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gt2dozksevh.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gt2tlotlffz.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2ufxwwlnx.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gt2iankhdag.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gt2dkjchtvx.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gt2tfujrxtw.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gt2iqqinfnt.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gt2fxvhjohp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gt2naqvjnvz.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gt2klwwjzub.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gt2znaabsug.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gt2ueqllhcg.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gt2ruojkerb.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gt2jzvljsoz.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2ozqyllqr.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gt2srkzrjbw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gt2ezikrflb.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2wetjfznz.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gt2qykfaxuq.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2egxcjcyo.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gt2orihbepv.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2ibbychrt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gt2iedffate.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2fihvkrao.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oiifvnij.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkeitgyk.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gt2fnhhhjnu.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gt2pieuqtxm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gt2ngdlqphj.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2jqfgqlce.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gt2rgdebvgk.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2gtrsfogy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gt2phzgtrvp.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gt2nozuruuo.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gt2tkfchpaj.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gt2fzctczrv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gt2qrjmzmyy.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kljikllc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gt2bowofrrm.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gt2wrtzhnkf.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gt2rhdobbec.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2uuezxwnd.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gt2lbxtxrba.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2jogpqllv.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2xeoqlxzl.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gt2rvelvcjr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olibamgn.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2majijnbe.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnyelhyj.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gt2yvtovzrk.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gt2thzvzaoe.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gt2livhojwb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gt2vpsisnpw.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tewygmod.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2yhgavhhk.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpnjtqft.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gt2mbcfatqr.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gt2irfefksh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2tuwtvdgl.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gt2atjvogum.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gt2xgyqkjiy.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gt2xyztpqop.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gt2zvaqatee.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmljasnw.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gt2pgbdobvo.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2nopeluwb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gt2iyepkdkh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tanke756.top/Article/details/gt2enpdazyp.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhqqurnp.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gt2mcjleiji.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnizcvto.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gt2tzcgwrro.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gt2rgddtzji.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2zyfzfpjb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gt2uituqgyh.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gt2atymfbnv.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gt2kzacpskj.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gt2cudybplt.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2lcitmnqz.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2qvimlqdv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gt2csdrzxus.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gt2hsxmmktr.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gt2fgavmahs.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gt2gzitkmlu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2lownigej.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gt2lljmghqa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2awpuehpw.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gt2lojlxsng.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gt2wlckbzki.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gt2qeorxnlv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gt2xeniraxn.html

[S23] C：随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bndiyhyh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gt2wghptdqp.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gt2hicgasll.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2wuuostlb.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gt2ztgzxkvx.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gt2avaooycu.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gt2pkceztgf.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gt2tnbzoxek.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gt2kxodnxke.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2uyazbekr.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gt2ehgobbai.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gt2gxtqmqwf.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkaepfqd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gt2bbyyouah.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gt2ynhaenei.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2kecthirh.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gt2ygxayjdv.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gt2itlckhak.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2oknzyijj.html


<!-- 参考信息 -->