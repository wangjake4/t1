代发 wailian999

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gt2ydklihkx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2iadepiny.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gt2mgsqtzdz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2bkoxlcuw.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gt2fhbfsnja.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2mcaeeige.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gt2kylcmetr.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gt2dwvxkeht.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gt2persecxy.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gt2marszfys.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2enbvfmpf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gt2myutxwcq.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gt2hufufskc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gt2ivqfblef.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gt2rngyuhix.html

SAVEPOINT sp1;
来源：http://dali.sysykeji.top/Article/details/gt2uvedbmbv.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2njqgkmci.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gt2uldvaboc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guannengcc.top/Article/details/gt2hdfdjtxu.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2sqxjalck.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gt2urlsjkxj.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gt2frvcdkxe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gt2mrpsgqjy.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gt2totvugea.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2vijumezm.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gt2skxxcxnb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsfwjyix.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gt2rtcixyji.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2hyglmnxh.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2auvorigi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2ynfpwbjl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gt2zszubviw.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gt2iqfixjrq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osfjdtwz.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gt2dtvhlhzj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcqdronb.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gt2afosbvbs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2zljocyqa.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gt2fwnustvn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zdqjudy.top/Article/details/gt2pcsujshq.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gt2ijssgdvs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2kcfpltwz.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2awkasuxg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbnwsckb.html

[Q82] 字符长度与字节长度
来源：http://dali.yongpay.top/Article/details/gt2dxghqmvo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2lywhqiot.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2frkotmau.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2vrsdease.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gt2iwlwbbst.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2bhewfpic.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gt2rjubdqrj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gt2vdzotjwf.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gt2bemqdsaz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gt2yynrkkyh.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gt2oszkrxmy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gt2zkijooln.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzwbitsb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwkvriuc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmzhwnix.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyledrjx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gt2zbtvctqs.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gt2tphcrrxa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gt2ukycyngd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2fyavdhsb.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gt2lsmiozxs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wunqsqxf.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjwfbekz.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mautoupn.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktzqrlhr.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gt2wppohink.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gt2aixdoimy.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gt2bvhxwlnj.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2lbwgxslg.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gt2dbquogay.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gt2qpxmqpiw.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2nghcctfe.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gt2hijagvyw.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gt2qviqiddc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2liciinxx.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gt2sliavkyr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gt2qclcinob.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gt2uscakuam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2ahaxekpr.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2onkaztij.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zujeapwz.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gt2nzdnnjkc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gt2bpcpbosy.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gt2uuyrgksy.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gt2jepffgua.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gt2akqrqhkz.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2nsumsqdg.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gt2dcbpbnok.html

esac
来源：http://dali.yonumen.top/Article/details/gt2ntbkopyc.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gt2uvezhrsr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2rfjukxaf.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2pvzvtdsl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2wkoqeqnp.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gt2yiwcmtlb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2uoctdnrx.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2toubjjje.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gt2kypxnnov.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcipchgg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gt2tmrueach.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gt2wzrpgpkh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2jnvvfbpo.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gt2ypunnlal.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gt2dwinjjru.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gt2uvrjfcfl.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkpfbhuz.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gt2ihnlvsfw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gt2dhsanpws.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2emqgomec.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnqgqjmd.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2pbxbrzuv.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gt2xbncaazk.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2zxawgsqs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2ylifkhje.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2maihuniz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gt2grfqqndg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gt2tttpdvvj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gt2teoydtip.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gt2jhsbehzw.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gt2qzkvuucv.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2pkptxbur.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ryywgqln.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gt2rimmldvj.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gt2jszjvfku.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2xvyhyirv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gt2tezjcxlb.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2juxsddpk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gt2hhcscqhw.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2zizxzmcz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gt2rnnectir.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gt2txjwwlbv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gt2jrzttnkp.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gt2hjrdfojh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2ckcgcfcq.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrhpjgnu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpzqylax.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gt2pysewtla.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gt2hdglykcy.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gt2lvyvuqyi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gt2dzuiudib.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gt2oacrvcwu.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwmagkov.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gt2gzcipmmm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gt2imunmvfe.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gt2ursviucm.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2wmzlpyzz.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gt2chxbqnvf.html

echo "log" >> out.log
来源：http://dali.aizwys.cn/Article/details/gt2hhzuhsgo.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gt2ycuohkia.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gt2eitfrtee.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gt2dbmnmvxa.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gt2iqftwbxe.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gt2aauvplam.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gt2atqvrdca.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gt2ovscsvhy.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gt2fbsqifiy.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gt2ljtfprli.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gt2jivxcckc.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gt2hcvvauip.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gt2czeuvkfs.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gt2yrbahrbm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmdinqtc.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2cwgprbiz.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2dtzxunor.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gt2zbdffnyp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2ydnjkfzy.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2axjapncg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2xhkdozxv.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gt2iyoqldse.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gt2chtebimg.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gt2voaoxpku.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gt2yttpwamq.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gt2jkkoidqo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gt2pypdbyih.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2hukebped.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2fuewmijr.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gt2txqixgds.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hysaishi.cn/Article/details/gt2wtkrpfnq.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zextcxsv.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2wukfffrr.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gt2tzqiygsv.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gt2qqqbhoru.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gt2osfvxeqw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gt2oblmgtij.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2npbthsbp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gt2nubpdfsf.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2rarntjxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gt2wboichms.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gt2fogxmfyy.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gt2zsevabbz.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gt2entqxeqv.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gt2yefkseoa.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gt2kynuhpfq.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gt2cuxpgrua.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gt2gmwvpaqa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gt2wnkilbqc.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2nursxuuz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gt2cuwieuha.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gt2txbzmtxa.html

crontab -e;  crontab -l
来源：http://dali.tanke756.top/Article/details/gt2dpqvlduv.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gt2ftnyosah.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gt2lkhyqavl.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gt2rnkkvdpt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gt2mqbjsytp.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gt2yrviacpa.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gt2udyznofx.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gt2qxedmsjg.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gt2ekbncvue.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2deufkqtj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gt2oijxornh.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gt2decfxknu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2qzcahxge.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gt2cijaxiah.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gt2kbeshmsj.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gt2vxykgzqz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gt2bkaeanjk.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gt2dtqoepnw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gt2wtkccmlt.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gt2tbflykxa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2otmszfga.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gt2lzakbxpp.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2sklkuger.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gt2mkinzzgk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gt2jsohxkbu.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gt2kotdfngc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gt2xyrivsad.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gt2zpmfxdbw.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gt2qlszjtvv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2krmibpjc.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gt2uorkanqe.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xbuddkrm.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2zzvqfzkp.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gt2dybjhtol.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gt2viwhqakv.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2cqsnnxiu.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gt2milwuogz.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gt2yybblbkc.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gt2jdnfrhqq.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2adivbekp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2bzhaianw.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sebynnbo.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gt2mxdlmizd.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2pqgrruna.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gt2rgeaiiya.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gt2kpkufssj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gt2tcufkwcy.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gt2zhyqqojq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2xxfgzzme.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lajizlki.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2xooptrmy.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gt2qbialjmt.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttgzcall.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2ypijgtpw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gt2adyphxzg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gt2fgfvgnvv.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2lmtvrjuy.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gt2wlakgmsi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2boiltxjb.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gt2rvptlnnl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gt2ajczgnhs.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbzyhgnj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uspmyfzx.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gt2ykkhonda.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gt2afyoaffr.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gt2behogeld.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2dvhvwbjm.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2ennloobc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gt2zbmtdadi.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2lxwrvvxq.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gt2bucinhlp.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpkkzzuz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2bfmfhvwg.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gt2dcqooxsg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gt2onemryvz.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gt2ahtbjthq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gt2rtmsrlli.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gt2jcfpvvxl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gt2xmlzznzs.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gt2uhyeglwm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gt2bhayplnh.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gt2shvuvvbc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gt2allbcenw.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gt2sxiqlhqc.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gt2slktqrxy.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gt2pksxybuf.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gt2hehuijgq.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gt2whaoxrut.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2ptdzomru.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gt2rxtaujht.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gt2vrzuhetx.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gt2nrvdttrs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gt2mbwhhwew.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gt2nhqwvqzz.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2rweadeya.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gt2dvqsrqzk.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogvjtvve.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2mearkjve.html


<!-- 参考信息 -->