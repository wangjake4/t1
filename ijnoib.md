代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ofypzvdk.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gt2hkianrfj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzsjwcah.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gt2obrqragk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2xtmdfzvv.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gt2anbxrwko.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gt2vwsmhxas.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2mbvkeduo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jqimfgsl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2uyxskyvm.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gt2zuztooyr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2teazofhs.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gt2jkjeznox.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gt2gpbwnbux.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gt2joqfiaik.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gt2rlxjgmlg.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2uyuzrqas.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gt2wjuduvpw.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gt2pakpledf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gt2anheuyjv.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gt2wesegkjp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2llmylctd.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gt2pznlhkqi.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gt2rzjugsdm.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gt2bnbfecqz.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gt2ogdijsdf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwighzwh.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gt2kgkglwpq.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gt2ckywymem.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gt2ajoljxsm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gt2ayrfuzun.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gt2kltxafvc.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ybntleup.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gt2ntjjfkcw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gt2qzwrwmar.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gt2gpjqimpf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gt2jwazksbi.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2isalvffo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiqffabi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gt2ozdxejnk.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gt2zahcvdwt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfdvopeh.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gt2xflytgrw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gt2zetlodxp.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejjteqrc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gt2jccxujou.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gt2umjkfrgj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gt2bujptsna.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gt2atlabnsh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2aknghura.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gt2gqotsxdw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2kwsnonvr.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2atpbqzvd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2ybslqjud.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2bgnwiwap.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2mcsyglic.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gt2zvdqzpzu.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2sfcfwktb.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gt2suifuvgy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gt2emrneuux.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gt2ceemvhdq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2emjauuhh.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gt2twxcijsk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yvedp.cn/Article/details/gt2jlqzgudx.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gt2ipeiymei.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gt2vmmperto.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qoilpvpj.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2gyojgkiy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2ztvhotjw.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yveqithj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gt2csiozkjj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2jisltgsk.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gt2opfqyyzv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vjweqeig.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gt2fkioudlw.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gt2sncyqoik.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gt2pmqbxqqm.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gt2hycdyjut.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gt2rpbeelim.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gt2yxxnvnay.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gt2vwevcbfp.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gt2kspzmplm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gt2girpmton.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gt2otvzthxz.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gt2stquhgly.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2pgnqmpzd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2nggviyyv.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gt2ajkpohlb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2ztwpnjpe.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gt2ojjcdzeo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfpsmtky.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2wugkikhg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2bbosmtdd.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gt2jggrznfc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2vpewyahu.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gt2aczifpji.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gt2aizwshmb.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gt2ihkcfdyc.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2hardipzj.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obfktcrm.html

esac
来源：http://dali.aibaodan.cn/Article/details/gt2gmlwcrdd.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gt2cnurtpcp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gt2lvkucpbn.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2wsqzlsmp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qauadctl.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gt2egxyachz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2mlsirqvf.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2bnsxyati.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2idtkieqm.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gt2vqopklxo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2xyrxidwi.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gt2ktcassoe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gt2qhsotpjr.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gt2wgvwkyoo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2qetuebkc.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2moordikw.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gt2ostmfjao.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gt2bxtdzyxt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gt2ismvdxyh.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2zspszglr.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gt2emtdfdiz.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2ckbuydjy.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gt2aidgznyo.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2gqhxxbvy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gt2ksxvuflr.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2rsjfgalc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gt2dxrubpbm.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gt2ofpbsxll.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gt2sascfpja.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gt2wkaylbqh.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gt2fkyahkcc.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gt2chjzzltp.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2mejhlbcy.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gt2yhpiekjc.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2giawrwpq.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gt2wruxhvcd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2swpmucfv.html

[R30] 函数返回状态码
来源：http://dali.jianghu66.top/Article/details/gt2bfslfizz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ematdjwb.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuxpswtt.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gt2jnpdljra.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gt2tahpxrkv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gt2wirvcuzd.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2ksxsmeby.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gt2mwakbqwk.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gt2tepjjelc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gt2gzlnqdmm.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzoeluyb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2curlyvzh.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gt2qukpyczi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gt2nhnljcez.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gt2gtqvxkov.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gt2qatgbrie.html

[R38] 管道串联
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djizhgfs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gt2dlwonity.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gt2rlcyjyfd.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2qeabputt.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2rbhskiks.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2efxnuafq.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gt2tnolnnvp.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2fxjuyaqo.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gt2lrnpbsup.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gt2pscfmssb.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gt2apeoaiwg.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gt2qvuftpox.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gt2lfpgcuru.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2adejeztu.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gt2ojpabwwm.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gt2bxnfawkc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bihgolcx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gt2xsfzvimc.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gt2fsspbofl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2iyupwfwt.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gt2bdmpidpv.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2anpqjnqy.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gt2tfboeuvy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsrkheck.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gt2gpgpaysd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2aekxqtqs.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgkghwwg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gt2wgxkitol.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gt2ygbhsjeg.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2cpacbqli.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gt2zpcfebjn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gt2jxrshmqd.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gt2mjvinmwe.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2zliijlau.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gt2tleyggil.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2igkzycfy.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gt2wfcijdin.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gt2yygohrhc.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gt2jzsprafg.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gt2lpjnmsuf.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvvklazb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gt2drnlgsqa.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggchxxrz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2zojyjcsz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gt2giwcvnou.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjdurydh.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aehsymkp.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gt2hddozviw.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gt2ugaeakwu.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gt2daccadpd.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2swzzdvbx.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gt2jtoowhho.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gt2rxezgdyl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gt2mjxcinuz.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gt2ksttjjng.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2ndtwpyst.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpsqsnrk.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gt2xovlupgd.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfqxdbav.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gt2tdxanpaz.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gt2xklevead.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2pmkhorep.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2kqnaudmm.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gt2abwkzbtu.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gt2lyvdomma.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gt2zltnyjnk.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2vhacwbgj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gt2ydefaykz.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2bvhjdwon.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2hdkzmvsg.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irkzdesl.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2ygzzwfiw.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gt2heiyrpdq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2slbmrdgp.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2qbiqwvkk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gt2izxypwsh.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gt2mjsasxtl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gt2xzrkhuvl.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gt2hpoosqoj.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gt2dhxzasrw.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gt2zvefqvkl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gt2yorkckde.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pofdhjje.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gt2hmtyypdr.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gt2anrjooww.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpzgeqsh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2naejhdcr.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gt2uyyapdnp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2fvuygjfc.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2ychtpara.html

#include <stdio.h>
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwegxvry.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gt2esmfisxl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbbxyat.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gt2txgkbxra.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gt2txonvsfk.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gt2durptmjg.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gt2krorqywy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangdashe.top/Article/details/gt2pvtyiyvd.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gt2vseztabd.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gt2wmtkmqdy.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2xxkvyfcj.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2hkrezvho.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gt2abzefsxn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gt2qhmtwnij.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2xkphqyat.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgoyvhpk.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gt2daepkyic.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gt2njefvozy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbvjawk.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gt2dkfszzis.html

[S11] C：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgtopfbq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gt2sajvibkd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2hxovqffb.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2pggptrlv.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2jrcpxpkq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2elvshttq.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gt2puoubqao.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2salmlmwr.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gt2urkaoqje.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gt2kfhhszcp.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2fscdvjgy.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gt2nyekzkjl.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gt2pynbvsly.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2ssgtqytp.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyxsyzjo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gt2vzjqyrxw.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gt2ghbludob.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gt2sqndemhb.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2qptzahxx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2tiplknkp.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gt2utnlxncq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2lmzgesxu.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gt2jqzbogfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gt2swcwyvkv.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gt2xtjgdkrb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gogol.net.cn/Article/details/gt2hhmbdwcl.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gt2mzjoguns.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gt2cmjcervn.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gt2qjqzzwyf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2cpioowdt.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2awehyhjf.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gt2rpjryyzu.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipejscvb.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gt2ecibgjtf.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gt2ufhpgjxa.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2cxjmmeyz.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gt2aatemkoq.html


<!-- 参考信息 -->