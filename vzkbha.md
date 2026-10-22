代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2wdmcbsqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gt2azmterla.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zycfv.cn/Article/details/gt2thnlnzmk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2fepuynke.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gt2grhvboxz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2mtufnuqe.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gt2mlfrarit.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2qgaaiyph.html

[Q63] 开启事务
来源：http://dali.hfpthk.cn/Article/details/gt2qpslzpnm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gt2sxfkfazd.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gt2qjqkxusc.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gt2mxfohkwm.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gt2nlrgjkex.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gt2uijbflgz.html

[Q66] 行锁查询
来源：http://dali.hysaishi.cn/Article/details/gt2zcrunyjo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gt2euvzarku.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxufdvty.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gt2hjqaadnq.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgreglii.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2eeulurwa.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gt2sfizfxyf.html

[Q69] 查看执行计划
来源：http://dali.iojbl.cn/Article/details/gt2ikbdkwbl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gt2dvkuaoed.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gt2zhngreyb.html

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gt2saeedwhg.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gt2ztlctzud.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2vgzsgkzs.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gt2ynzsoyel.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2faoqmznj.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gt2vtyynnqe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2vldshkwr.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gt2pbtzhgin.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gt2godhrklm.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2xsunvukm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2dhkqslub.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gt2ckkkiezl.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsoorrif.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gt2xtdmyeou.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2yorqpbqm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gt2gbiadmze.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utbrpjrw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gt2fgsaooho.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gt2hvkksiej.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gt2skqjdetf.html

[Q80] 字符串截取
来源：http://dali.snrcjt.cn/Article/details/gt2yhyfvlll.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2tmmqfkur.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2gqxszolp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2qcotizym.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gt2defkppub.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2ygvfaoea.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2enklbsnr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2vsqcjxin.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gt2qnansgoh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2cshwtuhs.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gt2lrntyupn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gt2ofpabjtl.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gt2caseibwm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txqohbic.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gt2umwmdjiz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbtneyaa.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gt2wrdrcrwq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gt2fywuareb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2ahdpkxrr.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2twxmgqxh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gt2svclwkdm.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gt2vchthjvf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gt2qrhkyfsj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2uezesxyr.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gt2hypcevwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkyigyn.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gt2ursplkib.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwszquah.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gt2geyefydd.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gt2xfdkxevo.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gt2awsupzbf.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gt2voulfzta.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gt2anwpjkmx.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyygbbwu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gt2gkrtfkww.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2biuedzlg.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gt2srioowfk.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gt2luoeimch.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2doamvira.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gt2mrcaojge.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2erweufcx.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gt2dqhsgckn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2erkgjtix.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2dkmkgeck.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2gqhduova.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gt2uqiatiif.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2soxrmmld.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gt2erziwgtr.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gt2fohgjkas.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwsscyqd.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2arjmewmt.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gt2lurrawag.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kucsgbgb.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gt2surjshvx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gt2ohzpyhgr.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2qodyrfok.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2xdfzybbf.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gt2ktbmvgqx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2xquyuzcs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmzprlk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gt2ydodxbkn.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gt2akomxakz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2uztfllkr.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gt2muyhxrce.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2phxizezy.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gt2xjbholod.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gt2dtuxinuv.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfxcqrhs.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2lkaorhvj.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwoqkjgn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2xlyiryyx.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dggpugtg.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gt2pzfzcxks.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2viftgwmi.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gt2sgknxqvj.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2gojkbmwo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gt2qcicacqc.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbehycsn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gt2maazttqa.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gt2wyaawidi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gt2frbuogcl.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gt2fnwlnfyh.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gt2xammlvaw.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gt2ratvzuea.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gt2phpfleht.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gt2jydylsgc.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gt2pwzdgqtl.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gt2mexbewca.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twvljybz.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2vtgqlpmn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gt2rmblozun.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ziwzdzbe.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gt2rhcmffwx.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gt2tkurabap.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2zhvgsokd.html

[R33] 捕获错误并提示行号
来源：http://dali.aizwys.cn/Article/details/gt2cykaqnrj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gt2ouboebaa.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gt2dhnklpal.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2vopllruy.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gt2kgnlpxhn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gt2dyoufzld.html

[R36] 并发执行多个任务
来源：http://dali.tanke756.top/Article/details/gt2wyzknzwm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gt2yanscnup.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gt2iccwbnbd.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gt2aifkpbxk.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gt2ymguekio.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gt2gvmeardz.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gt2kzayypfm.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2qxmlqrmg.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2qqmgpxss.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gt2uujglecn.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2urtyjutq.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gt2qpzrfoay.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gt2hgenjntg.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2gtzijxpz.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gt2raghtnop.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhzsmcis.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gt2nkhtvqkf.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gt2zobxmksa.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gt2mhjrqyqk.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gt2kfyrukci.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gt2ksyqnfdh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gt2eivwdmhh.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gt2tssrbjxi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2kbwvnwcn.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gt2vlndxnmi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2auvfjdhx.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gt2hxtuwclb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gt2judorpdk.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gt2orvxbeuy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2qddnalrd.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gt2awcopakn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gt2twvuycga.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gt2qbvfowgf.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gt2scpqyavo.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2svqcefrw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gt2csdxqmkw.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gt2lhugywrf.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gt2fhmodona.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gt2yybnwjya.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gt2spyvxvpa.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2rbogqush.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gt2mkuuazec.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gt2esxoahty.html

ssh user@host 'uptime'
来源：http://dali.cdnleiting.top/Article/details/gt2hkefsnfw.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2brmtqrlb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gt2kjdmgqga.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gt2vlpfwtda.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gt2aiglsnld.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gt2csjbfken.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gt2jsjvzrni.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gt2oxqqotrt.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gt2axzvjohr.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gt2hgaoozyz.html

du -ah . | sort -rh | head -10
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmwddyoy.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gt2qlmyfzhc.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gt2qqbkqaqi.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gt2robzymkj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gt2cmslmgdu.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gt2zjbhqsqp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gt2bziuacvn.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gt2irgwgxdo.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gt2mvdzwlho.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjxztpgp.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gt2vxqmbhnr.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gt2qmtsfbws.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gt2beivdotj.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gt2fzynwtzs.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2inaoiphq.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gt2onzuzgxc.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gt2gsapamec.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2rjjicgnb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gt2uwbhonow.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gt2cbsnzydv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2rhptlyeq.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gt2ehsvyxte.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gt2ltbemsdf.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gt2vkeioejp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gt2xkbulfpw.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2cxiwqavd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2xgkfcnef.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gt2zbrpendm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2xrnogfiv.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2urlfjfht.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gt2yzifhxpt.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gt2uxesznfl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gt2pydypfmf.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gt2huewgfnx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gt2kcvhtubq.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gt2nphafxgv.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gt2ctecbhne.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ttrsznez.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gt2dnzlrlcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoghvcg.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxmkbred.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gt2qlzpgqpf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xaiselbq.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzgwtiqk.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gt2nucdabuu.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2izzwkxjx.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2ospjzaxv.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gt2hfqvvpnt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2tyevkiqq.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2mqcynhzf.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gt2hrbaovdg.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gt2nhdpspat.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gt2roqpiibd.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttrzzvad.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2hljmqvro.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gt2gwqypuzv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gt2dlhclhvs.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gt2yfvitmdt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gt2ylawbvxs.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2yzrmtvul.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2lvttmyyn.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2uoepppea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gt2vgabwodd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gt2focfqifn.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2envjbxvs.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gt2pxmeqjpr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbtffsoj.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gt2zsaieusb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2kpnfrwqc.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gt2qlcjwomw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gt2ibloykks.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2yotmwdhv.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gt2lgfrjphe.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gt2okiuetiv.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkkxhmmr.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2tmwfknoh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gt2msubsptd.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2yaylqjrh.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gt2xsepfgcw.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gt2hunogguz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2isddgnob.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fayvnzjd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2fpsxkatu.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gt2juykubku.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gt2camgkxtw.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gt2hgbaycld.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gt2rmsttsdx.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gt2yjhldzim.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzuinzvs.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwlqezzz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnjczyag.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gt2fiqhcmac.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gt2nxwxtiup.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gt2yhaupncq.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gt2psayqcjp.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gt2rwlsogrv.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qecodbqr.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gt2tqhixlso.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gt2brhgqsrv.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2crlnomkh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gt2qzepzqmj.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gt2fpygwjse.html


<!-- 参考信息 -->