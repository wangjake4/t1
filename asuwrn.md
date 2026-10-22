代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2purnppyv.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywyffdjf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlyzifwg.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gt2qqsdtomr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2gpkfkavh.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gt2jiwadayc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gt2pijsvwno.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2ocfswehu.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gt2ucujnana.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2cftxwrud.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gt2vowlbxcl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2fxvoysqj.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gt2wguokcky.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gt2bdmqbpug.html

[Q64] 提交事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdhkahgi.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gt2fmsbwlbh.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gt2lteolofl.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gt2fugwdeds.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gt2xdjcjrze.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2cikptngc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kdafhimf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gt2ssaealdx.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gt2kwopwyjh.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gt2jsfkvoom.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gt2wybwsgsa.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gt2eqikqpfw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gt2hzbrlrug.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkcqyqxa.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gt2cffqdjwe.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gt2pgagsmtm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gt2dkdsooci.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gt2ncapnitk.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2ieenyvgx.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gt2hpptswhp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gt2uebpjkuy.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gt2emrqyzsb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dghgdhjc.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2lvkczueu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvwbqsri.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gt2svlwollq.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktgtojer.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xghqrlmp.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gt2cvtbjgtn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhxoprdp.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gt2mffhoypu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gt2zihzwafl.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2jdzqcjwi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gt2vvuxcpzs.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gt2bziobrel.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkattips.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2dmantffo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjgynlnk.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gt2sdnhtlqg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2enkssess.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2bojhmgml.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2gcqtyrxs.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gt2pcvvndih.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2cmfsansm.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtmnnqfl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gt2kujuiljh.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gt2trxkuzon.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gt2hcpwupuo.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opltikwb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gt2gjfgamni.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2ztqqcgjt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzodevgz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2tdajlqyt.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2kghtwwew.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gt2obwpuudi.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gt2huphxwot.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gt2hlorgsjq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ngzdoqld.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gt2ebkguqzg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2wfabjzqm.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gt2xwuxxicf.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gt2gvgagnsz.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gt2rfcmrdxb.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gt2wzhfinrr.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gt2biunmifb.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gt2gbmabpho.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gt2tnrnplyv.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gt2lqpqcjqv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fzhhl.top/Article/details/gt2iqsstvfk.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gt2jccqbwfb.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gt2baconnbu.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gt2agyqwqrs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2bwrdfsju.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gt2vlbfxwkm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2ftkxiitf.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gt2modialeu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gt2lsesaqvl.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2ujjdkyuk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2hjqvejox.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2nbftvpml.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2sjixiglm.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gt2xftiuynr.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gt2gxhlhifx.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gt2rhnbipxt.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gt2wmnargli.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gt2zxrrjfrl.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ileitsvw.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gt2tjctnwww.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2vbkatpbz.html

[R13] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgvxcxma.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2sqqiftaa.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gt2frrabpqp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2exudeyit.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2nxcvcvqo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2offvhrod.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2aabwgwto.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gt2noywfsgf.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2afaojuzw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2kwphtzfu.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gt2cabqsbkr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gt2zrkudxkn.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2mtzgzixo.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhwusvfe.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gt2qmfqqkve.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2fzoyseyt.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2rfietpju.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gt2vtjtnuwr.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2sdnfduej.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gt2dcbvdpof.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gt2szbhvgum.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gt2crzubzqv.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2kdwpacxa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gt2kvpjeawa.html

[R25] 去后缀 / 去前缀
来源：http://dali.meibo888.top/Article/details/gt2mwfiezeq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2aynjfgrv.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gt2swvvqwcm.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gt2eufxhgfr.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gt2hajnsnta.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gt2scwbdbkn.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gt2yywaqeni.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gt2tctxztbo.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2evqmakab.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gt2fpftpvpf.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2cnlyhved.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gt2hamcbsmn.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gt2esxlismx.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cadlkkje.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gt2qgmhksrj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2bbxfqmbd.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gt2yhgmkknb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gt2eawuwuos.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gt2cgchzxew.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2lctyoomb.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2dlmqltgr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gt2netazgjy.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2vxmtfyqu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gt2ppkjkfjf.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gt2fzqodwhx.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gt2rbzfvhkh.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gt2csgdmnae.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gt2rqkyantr.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gt2epzgimkc.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2zuthfztj.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gt2sdneomqm.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gt2rrzlmkin.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gt2tigxspqo.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2fzefiolr.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gt2ddfmsmpb.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gt2kvgbcxzy.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gt2zopxbbcq.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gt2uqanfohy.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gt2dqqrjewv.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gt2chfwlmcx.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gt2cvlyqprs.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gt2xeayinrh.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gt2kficbhhn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gt2ruxcvpxx.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gt2znoebkjy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2szmivlkq.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdcvcvru.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2oitftrgy.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gt2jtrrvisc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2asyvtaev.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gt2hoguvpgw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2btlkfxqi.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gt2rridurzp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gt2wzamugmj.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gt2lwplqdoc.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gt2xzwugzxr.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2yegxuhjm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gt2rfxdpsio.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gt2viojztvn.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2aorsbfmo.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gt2traeovit.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gt2bbcnnhan.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gt2uokqqgam.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2jivarsgy.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gt2tqbtbuel.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gt2hgrdseex.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agipwivm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gt2yudvspck.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izxouhde.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gt2wqqcjomu.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2aossvxzq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gt2cvbmnzuy.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gt2sfhigkdf.html

df -h;  du -sh *
来源：http://dali.pycfn.com/Article/details/gt2fxzwnciy.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gt2aonvimrs.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gt2uizkjwys.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gt2glqsmoky.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odravenj.html

[R64] 结束进程
来源：http://dali.cashguo.top/Article/details/gt2hahrldln.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gt2jsqkbomx.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iylpuetf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gt2asnyjjef.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gt2movqppso.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gt2gotykxwf.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gt2qzzuxdxu.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gt2rofntxdo.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gt2ksvcqwva.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2rqouyhzk.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gt2sbadxowi.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gt2fhvfolrr.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gt2syizhrtc.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gt2qcsyfxge.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gt2fxcqrgrz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gt2xzkuwjpe.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gt2fclohrak.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2fgsbfkud.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gt2qnvakqtk.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gt2mnllmhuu.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gt2fxuvydrf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gt2wttgdicj.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2rbxnvvca.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gt2lgwokxwd.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gt2zclawxfr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gt2ltjgszcf.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phrfddja.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gt2rdhfnkck.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gt2vuwozbvh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gt2sornojsb.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gt2ibnmhemo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gt2jgvbikfz.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gt2ekbhjrhx.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gt2uihaebsy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jqtkhpfu.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gt2wnqpkvxq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2rkhrpojc.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2awzopugl.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gt2ccdcrhts.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2anfqknub.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxrwzoan.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubtqsvxf.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gt2ritdxujs.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gt2sjnzpwex.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2tjmdcigc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gt2khldmcvr.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2nqmnndxs.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jegodheq.html

[S06] C：字符串比较
来源：http://dali.0kj1m.cn/Article/details/gt2otofvdta.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gt2soypeovg.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gt2yqlqzkot.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2zwbjmcsc.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gt2vennxlbv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzuvtmpf.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gt2uqkizxqd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gt2lkhzkaio.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gt2iatfrjvf.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdhaqqol.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2wlnrnkuw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gt2ustcfgum.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2chbtzpdm.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2vgdgpxol.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2madbbata.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2ykzjlnmz.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gt2iokfugrg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnkzihrl.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnlffziw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itikwlrq.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2kywhnqym.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gt2mcbefwyk.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2ievkudtr.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gt2fwrxbmrp.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2eoopnuba.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gt2rfbcrpks.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ccnqkbbb.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gt2wfdtepqq.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gt2mikypnpg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gt2jbrozuoo.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gt2yswtwtfb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gt2gshrmqri.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gt2srauatcp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gt2fqrvwfyg.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2nylpvsce.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gt2ekvxdegl.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gt2qyscrogs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxcpgoo.html

[S24] C：获取本地时间
来源：http://dali.xinyue.icu/Article/details/gt2jjkpvqoo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gt2rlsttbmx.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gt2wkwtaszl.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gt2njnjuupf.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gt2eozobwhk.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gt2bzpvmiwy.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2djdsszhq.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2zfoobiek.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gt2egqgwphr.html


<!-- 参考信息 -->