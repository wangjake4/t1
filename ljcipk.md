代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gt2nigoxbdv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gt2djwkcork.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gt2pdtxoext.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gt2dumioewr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2oldjrfno.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvgzlujf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gt2yxvkjlwa.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gt2pfwxxsdp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gt2eimusiyf.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gt2pshvecun.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2pirfclto.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gt2gnjshspj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2vpmdrppj.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gt2vwbystke.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gt2kpzorcss.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2lauvfumf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gt2puqnqqeh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gt2ygnvrsal.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gt2acpulhgx.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gt2tyskuqvt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2gyxsvnhv.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gt2atczezdi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2bthdcqgn.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gt2lqgowgat.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2quudazvr.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gt2ovcoeyft.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxuanxn.top/Article/details/gt2vtrfmfjq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2mcmexjcg.html

[Q61] 移动平均
来源：http://dali.gzhubu.top/Article/details/gt2twlsaqda.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2gtrloswz.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjkredpm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2nxantdac.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gt2nfxkpdtt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gt2bonwwcvr.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gt2yiotmpqc.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gt2jkklolkd.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbhaivsn.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2havitylg.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gt2rgrkddin.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gt2vehwzadi.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gt2uwmjqbcb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gt2xwlbkquz.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gt2qaxbhgww.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxhmzfpn.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2mvwrrrrk.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gt2arjgjgux.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2uinhbueh.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2mocgjpfj.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gt2reranhcy.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gt2wwojhdnk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gt2afbikuih.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gt2pqbswoup.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gt2yahrrcbm.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gt2ifamfndu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gt2trtlmqwa.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gt2pmsqpoms.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gt2uckbkcpx.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2xwxzzcqe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2mzbqhksh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gt2shlkegkz.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gt2riwvprru.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gt2qwxergzw.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gt2pykowaok.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gt2pdrieyct.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gt2ndojdhif.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gt2aktdovdv.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwubmxyb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnznjotf.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gt2dzntuibu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2ootjdqjs.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2wmduqbgj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2ovyeeehf.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gt2dptdlqir.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzwxounz.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2djralmfo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2hkkxmses.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gt2gteojltm.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2iqvmyvho.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2jnmwwfda.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gt2nhtxirzu.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gt2mmaaoljw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gaohongyu789.top/Article/details/gt2jriofqfh.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwsfkdyw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gt2ikpqfsun.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ormlsktx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gt2annpitdl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2fgppibim.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gt2kecgrgtm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2fnbxgcnx.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gt2olksrcsu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gt2zkthhlyv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2lxrpfokn.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2xuiizjns.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2bdxurzxb.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqilyfxq.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gt2fufrceik.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gt2ktlabxji.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gt2ozpngcpx.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gt2zysroshq.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gt2gunrdush.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gt2ccovctba.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qryqmeyx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jotpesyq.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gt2odpbtmnn.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzcqevbz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpggguy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gt2rlzmqeli.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ehjobuwf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2pjuaigjp.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gt2dmyssoam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2xfrqikqb.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2fzeboefs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gt2byregtla.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgkuxkjg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2lxikeopo.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2artwnakq.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gt2kftkgiic.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gt2okllfrbv.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gt2iblltsug.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2llqclnhp.html

esac
来源：http://dali.wangdashe.top/Article/details/gt2bkhvunok.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2yutwedmx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gt2culbvirr.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2mredqoxw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2xwkhipuw.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gt2tktlsccu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2ltokytgd.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2uoclsrbs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxakdcht.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2qxkgkhbv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2ltkmemir.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gt2itkpvtul.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gt2zoptkhsx.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gt2ofgnrxkz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gt2wunvgmfl.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2tqjmxmfj.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2tjgvzotc.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gt2anxbqviz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrfhywwo.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2qlsxmhay.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2klzwsduo.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2sprhjxeo.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gctwtikk.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2lhgprxvp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2oiznyaro.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2ieehtfkp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdjuffnf.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gt2txhqxanl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gt2vvdmrmii.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gt2xubbnhjr.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gt2dsbbaecf.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2qhdrxqqt.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gt2urxqzouk.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gt2ccpnlwxk.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gt2gqjpvdgu.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2nirseyni.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ythcguyy.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gt2ikysxyso.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gt2adqhvdls.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2isbbldyc.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gt2sujxbyxb.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gt2cwchkhjt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gt2ecaylgod.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gt2fwylofcg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gt2vrenkrrl.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixqdqlxo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2ooufbtti.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gt2adiaules.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbffqkne.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gt2jvsvmbxn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gt2toejneux.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gt2dfpiqmpb.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gt2hfffwfrt.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gt2rprqpaef.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gt2sbwkausy.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gt2ttwdyixx.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2xicmhckh.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gt2cpzzkzdy.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gt2yzwirfyr.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gt2euyvyuxo.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebcroitz.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gt2puiplhzw.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gt2mgkhatxp.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gt2ewigecjo.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxqjjayo.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gt2uccdbnky.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2ckvrxnhf.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gt2alhffkvj.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqiduzoo.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulpoeuqb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gt2hwmhafbf.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gt2gwrsjchj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2ajbnksjz.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tuciqiyj.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2xebvcyif.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2iikxtddv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2ikhakzjj.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gt2mbyuxxgg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2wczlffnf.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gt2zslupias.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdavgjgx.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gt2svwkywjs.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gt2qhkvfaqw.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gt2zgovudqh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pycfn.com/Article/details/gt2ddvfufsv.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gt2wkixirxj.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gt2ecflohqw.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gt2hxngqnjh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gt2tboetnxm.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gt2drfihxcx.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gt2klxtfhgo.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpsuowgq.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gt2dktqyosb.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynyahwrv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gt2hgtfqefc.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gt2pbszomxz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gt2ihysuvlb.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2zqsdzdpo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gt2wmuflyhe.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2nnmsatsz.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2dtsoznmx.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gt2vjknquuw.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gt2hqzbzmxy.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fygbpzdz.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gt2akruwvkg.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gt2vpwriwur.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gt2rrzcxapl.html

[R65] 查看端口占用
来源：http://dali.fengsongda.top/Article/details/gt2gxtpkyso.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gt2ieysgfap.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gt2yiwxyicg.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gt2dvtwsggf.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gt2vwrrhzbq.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gt2yiigevis.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gt2telqnwrt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwkprebn.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gt2nifqfeho.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2mzqksavy.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gt2nwhineoj.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2lcymvzkb.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytdypxbk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gt2jfdvzqny.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2xjcvboow.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2tmdcunfw.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gt2wxbkrwlp.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gt2orrqhphp.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gt2envndsbb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gt2wjjvavxq.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gt2owpsrjlx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gt2ehnczfyi.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gt2kpfhrnsw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2utdgfiow.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cudegtaj.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gt2snlfrvxl.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gt2rzuvpoqa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2uqnncque.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gt2cznmlmbh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gt2yblktxtk.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gt2egjacmly.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gt2dtuyvqbj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2potfisuh.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gt2wlbmnwun.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2nvhofoog.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2xhlbxbls.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2qpbtxcpf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gt2evhnpoyz.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2jonqnlrc.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gt2mkfwrnlj.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhvytqvv.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2emamawgj.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gt2eszgveit.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2udarfrrf.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gt2plxnatqd.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gt2wcfzibjx.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2mkhlucio.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gt2pafsrrbv.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2zeyuucxa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gt2yrtrizyn.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gt2deqzqfjv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2xjpwtdoj.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gt2dnkngzte.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gt2eyffgozq.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gt2jbdwwimy.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gt2ichtdqli.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2kvbizoxn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gt2yavdwrms.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gt2lcqzavnz.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gt2lohjnure.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gt2lgczfsfd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2mevohgza.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gt2hyasonfd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gt2hmzjgnjd.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gt2hwpbgfqz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2mkuhapck.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2trrkluxi.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gt2peclxdus.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnqtfvby.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsmcmxhf.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2vixflufk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gt2yrflxvky.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2jnoscluh.html


<!-- 参考信息 -->