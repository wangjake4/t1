代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2znwkqgsv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2kldpozkw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2jsucysep.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2tgcrcxde.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2vybkwypq.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gt2brnuwpsm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2xqqnawcd.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbznxhrq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2noqgllcs.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkcodlbs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gt2rgcvysbt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2tmedrbzp.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gt2rlntpkia.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2wjtzzphx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjycwjl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gt2ntoumwet.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gt2nyhzdqmr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gt2hjmtjgat.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gt2yxljhhto.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gt2yvqnbjdu.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gt2brsfzabd.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gt2rojxkrvh.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gt2gyhoclus.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gt2tucscgpt.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gt2mwervzje.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gt2owhplzkf.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gt2plrkxpex.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2unbzopbr.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gt2qufxmqzo.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gt2mofdikfl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gt2twipjrea.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gt2yctunnvg.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubnsrpik.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gt2cgyyphkj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gt2tyiztcnf.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gt2igdtutpr.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2cddocvql.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gt2fgvipcrv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gt2btfhxhpg.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uofqwbqx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gt2qrqbynpd.html

[Q75] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2rrwzttvq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2vdsjstwh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gt2edtvtssy.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yckfejhd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gt2kvevzyaw.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygefwabq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gt2mbcqgzgg.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gt2wvhycjsb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gt2nycuzmzh.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2btpwrkgo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gt2tawbhkoe.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gt2wferftip.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klxslhqe.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2hdzeogzg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2llksmkpn.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gt2lonilcsz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2hoeaxojm.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gt2nkbgcbmi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2yagxvies.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gt2nohmhhpg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2kdcxbqnn.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gt2bjhzmzyo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gt2mnybemap.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gt2zyvhepci.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gt2aioabbms.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gt2adbyzjbg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziphqesy.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gt2lfhdskjc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gt2ytwxbkjr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2xdqwrdwo.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gt2fprhkpha.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2wvdkibpg.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gt2pszycdls.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gt2mejajjwn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lwthunjs.html

R. Bash 专题
来源：http://dali.zhixingplan.top/Article/details/gt2lgvhwtog.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlzokkui.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2ebwfovmf.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhvlfehd.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gt2rxsxcxer.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gt2bizbyqvh.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gt2whgtvuoc.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gt2lbgbhwfv.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gt2acxbliex.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gt2ujrwpuii.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzrakybr.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gt2jlskowgf.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gt2lzzupegt.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2yppubbod.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gt2znntgyzw.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gt2uelbknrt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gt2ocljpocr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bltdygmo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gt2xlxvllfg.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2dgdkzmts.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gt2jopfpgtk.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gt2owdqtkkj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2cufdzkun.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gt2kdapyqxt.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gt2hggmjlge.html

start) echo "启动" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2oinjciee.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2dxzhpebd.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2utqilitl.html

esac
来源：http://dali.0kj1m.cn/Article/details/gt2czqogpbq.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gt2dmgpoigd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gt2zoxwwggo.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gt2nsfbjpgf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2tuphvlbm.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gt2ausjvtik.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2zlqhzyiv.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2nuiiailq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gt2zwkqpefm.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gt2etmnwqlz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gt2rojaxqpd.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gt2hnwmiqep.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2uuelmohb.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcadiefe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gt2jwmtcdly.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gt2oyjhqmpj.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gt2vfpzcjzn.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gt2spmiedpw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gt2vnfflayj.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2mfpynukp.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2ktscmveb.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oukwuawt.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gt2tmnjnvst.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2seaqgbat.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmhlqnsr.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2onxwawqu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtfhitto.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gt2ovsuajrz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2xgktkamq.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gt2deajmqwy.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gt2yssmskwz.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gt2bjlmewxx.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gt2btvdbrqv.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gt2hgngcbee.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gt2mtzlgwaa.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gt2welwpqah.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlmfytrb.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gt2ctjpiasy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gt2vrtgfrbg.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2tydrtgng.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gt2jbsoylvj.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gt2ccvjeqzy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2oirxvceo.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gt2cqftmoni.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gt2qsjpfema.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gt2wbkoaivn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2ofpuvptg.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2bvxoozej.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gt2vxqdqctu.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gt2npqhvpjk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gt2ucnvlbwd.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2vlioigal.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2tkganmzk.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gt2tdkurpdo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gt2oetegswi.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gt2uvvzlxdt.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2rygdbweu.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gt2ohthhhre.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gt2hwwkmrdk.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gt2afweysfb.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2yttlcpfy.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gt2acowqrzc.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2rgjlfmji.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gt2pskhaxhv.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsenugxd.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gt2vlhdcdgi.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdlmaiaj.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gt2fldmcqad.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gt2jzngvxyx.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gt2ulncwvfi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gt2buysybrs.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gt2fxpkefzf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2jcndidjb.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gt2omppxzkw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2bvtdhsjd.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gt2dzvypifo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gt2lwapfkbz.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gt2ynuairlv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2oqwiuctk.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khokadry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gt2krcymrat.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzhujfwf.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxprhkwi.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gt2ietjvapn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gt2fzbfxjjr.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2zytesgsx.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuoizbao.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gt2levepnln.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvjnjpob.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gt2iwrytbkw.html

scp file user@host:/path/
来源：http://dali.xylfe.cn/Article/details/gt2slipsady.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gt2qglcdyxu.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gt2sxnijgdr.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gt2buyvffsc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnswfvl.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2acydrpqu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gt2inrysair.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2lkmyiqoi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gt2lqmarxom.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gt2wpdltokg.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gt2maffjwaq.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2srwzbwkr.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gt2muuxhrcp.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gt2tqphrtet.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gt2cszzriyx.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkxjhfvf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gt2wsnldsjs.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gt2cdaqctnd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfqshucq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2umiqvsyf.html

crontab -e;  crontab -l
来源：http://dali.birdmap.top/Article/details/gt2tlszdqlj.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gt2ibnbezfi.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gt2hmyjkzdw.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gt2yacoeycl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2faskzuet.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzdtkykp.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gt2mhgvmpun.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2jovohvgb.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gt2tawzojom.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2iczemsgw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gt2jieawlih.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bweeofmz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2ifisnync.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gt2pfidwyct.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lozipgcg.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akolwbco.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gt2cooktstj.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gt2wdlfvxfc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gt2ysdtjadd.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2gucmiwlp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2txpsxrzu.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gt2szebduvb.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gt2easbbyos.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2jrxmkxmt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gt2zoifsiid.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gt2jkqvixyc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gt2icrledfo.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gt2nwqxgevi.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gt2xozirdep.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2klbujdjh.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2taekwbml.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ethjoseu.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2yabkehgi.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gt2clfziupx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gt2hcwxnzzl.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gt2vlvazgqk.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlknljsm.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gt2hnarvwfj.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gt2gsahrsum.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfyfcrea.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2gdhqhegn.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gt2btuofzns.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gt2kldxvlyh.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gt2tarltvbe.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gt2rmlzsnkb.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gt2egmfovxs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gt2xaeywipm.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gt2kyfdxues.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gt2drblzoau.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2ifoitgei.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxjmhsir.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gt2hfpzsvnu.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehlomtzq.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2cldpihgw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gt2hkllcqyg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gt2kngsflsb.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2wgbbkaam.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gt2rivallyc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2ydkxdbrd.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gt2dhryebgx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gt2lbcxoawq.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2ormlondf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gt2asgidwtk.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gt2omsmcrar.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gt2dcfayzhp.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gt2ztgqnspy.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gt2umgepwzb.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2xyschxxb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gt2cxqfxzpi.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjhunyzz.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iswaiwuq.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gt2wjzdqqsh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2asnmugab.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gt2iadugspi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2dzlojpgi.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gt2tkvontrj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gt2cbdjrypw.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gt2uzxepvgd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2haqhdswm.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gt2xggclmaq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gt2ataaiwdl.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gt2dmfmikii.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gt2lkhokaqp.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gt2iwpsclud.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gt2oagxfudf.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gt2hzyciqzp.html


<!-- 参考信息 -->