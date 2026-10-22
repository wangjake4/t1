代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2rtujxkpt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gt2qgapucjg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2avegydcv.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gt2cbejshvv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2zwoexpxr.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gt2petoqbqi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2vvwyfxyh.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gt2hbgqelvw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2rklkxtwr.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gt2fdubhjwo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gt2cmjmqrgc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtrgwynz.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gt2lozmmpdx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2zerstvqj.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gt2tmvlpvbt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gt2swsowdbp.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gt2znzbsefv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gt2dcqyzxgv.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gt2eusqlhuq.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gt2iualolwq.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2inwyszud.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2mkqwnjcg.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqfzvmsw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gt2qshbzjcr.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gt2tlbjyefr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gt2jvcvnjoi.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gt2tuwqxido.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2wzxureqy.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gt2nkwwyggq.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gt2znyhgzcq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gt2zssgiqgq.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gt2jkmepapt.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gt2hfjtfkml.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gt2dratqvzo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gt2afqkboup.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gt2wkunlwgr.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlbsqzgw.html

[Q73] 查看表状态
来源：http://dali.ybcxt.top/Article/details/gt2knvkmady.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gt2vwobkfka.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gt2srlktdiy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gt2nnztzzbg.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gt2himkbrqw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2poyqzwdx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uscudwyr.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmgkmgoa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gt2wzgleqml.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gt2qicttkrt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjtsakxg.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2anigpafb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gt2jwdqtrfm.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gt2sukewocr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gt2ozyleesv.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gt2ackkmttq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jldwngdx.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2ofufiues.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2gigbeusr.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gt2unswxzqc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2eujbosmo.html

[Q83] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2dwncjgms.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2znfwsjxw.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gt2wlnppagu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2nysykpcd.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gt2tdocmxaw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gt2lgzyjspt.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gt2nrpwetfb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gt2jtkwvbow.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gt2kbyvjkus.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gt2tignqrjb.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gt2iqabwwbi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gt2omnbjiih.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2towqficu.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2nhihskzu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsufmroq.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gt2nkhvhnny.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gt2ybxbtgek.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2qqkwdfcd.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gt2qgbdmtzm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2mcnlgfag.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbdxszxk.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gt2saycojoo.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gt2cganbcdb.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gt2kfglrvex.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqpueibc.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gt2ttugxmrv.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gt2nmtqpaym.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gt2ctvmpdco.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gt2hrvnzgbx.html

[R05] 参数默认值
来源：http://dali.316326.xyz/Article/details/gt2wyyquxmw.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gt2qkcculiq.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvcwnbhm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gt2xguysbds.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gt2qmgdrhgt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gt2msnoffuv.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2ksrzcmav.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gt2aclekuyh.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2ymbsqywz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2mmgamxkv.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gt2ccxhmvav.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gt2fkbhjlri.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2nhpoitss.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gt2tjxbqita.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gt2kosgauzm.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwtqbltm.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gt2vtylaryv.html

esac
来源：http://dali.yuanzhike.top/Article/details/gt2iahiqtkq.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2ugzxlkfk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gt2yssuzwzm.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2fjsjhzww.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gt2khobaoft.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2schsnoea.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2abuuvdky.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqdtdgie.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gt2dwfzgchi.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gt2gbarzsmk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2zzhhzvwi.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gt2crsgtdxq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2yppqylle.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gt2yhypdspi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gt2zdjnaqyt.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2cllwsurs.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvdbximy.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2lauwzapb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gt2afmsxora.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2xoemnuuv.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gt2muxhgxft.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2okzzeqpx.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gt2jgpgrmqe.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gt2hlavybhc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gt2vqsfwtlp.html

[R24] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2oeumvtxz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjcvkefm.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gt2mgeizzae.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2curkeacm.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gt2kotfqvye.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxdafnfj.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gt2utobtmjk.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gt2kttbmxqx.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gt2ugmrmhdc.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gt2zyxvezot.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2qakmyqnw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gt2qlweossx.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2pspdvvdr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gt2vhscxrrk.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gt2hiabyxdd.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xnzkdjzr.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2tcdvtlvi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2yalqmqbl.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gt2fsqqgyrm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2gobtdydg.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2ouufikfd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2dpuidkuj.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gt2mzyxysgh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gt2cfxycsza.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gt2mvskgmer.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gt2rllereur.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anipcpev.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gt2cyowitzf.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpaaadrk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gt2gidurxzl.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gt2hocnoutu.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2aygtxyda.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gt2liwziuli.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gt2jtyqfyiz.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gt2iedpjlfi.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gt2cepregnz.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2nhjxwszf.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2ambpkwup.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2gekyuzed.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2dfjhmpkj.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gt2bffcprmc.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2hhplpofp.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2kfuliopk.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gt2fgbzaflr.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gt2bxkcowvo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2opjfdpev.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gt2gejxfvhx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2jwgncukr.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yagdeudb.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gt2wyposusn.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gt2zsaffzat.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gt2xrnrvdop.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gt2fbyiwoom.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2ntnthgrt.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gt2avmipiks.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gt2pjoyxouy.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eapmjuas.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gt2emrflulp.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjirypee.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gt2motyudep.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2clrmlepi.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmdtzxlc.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2sldkudnu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gt2vnvyrgqs.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2gmipdkcw.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gt2vgeyppjm.html

[R57] 远程执行命令
来源：http://dali.svipenyu.cn/Article/details/gt2uaflhpum.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfdrviuf.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gt2pkglmmvg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gt2txrbucgo.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gt2cwzlnstg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2jioibvaw.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2fzzpvrmf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gt2ssppobcr.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gt2wupxreyq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tualnilu.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gt2qwwspaqy.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gt2ehfvwcfg.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gt2mbxoffzo.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gt2kqskoxrd.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gt2hvhavbwh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gt2mtyrreuw.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gt2beojjlrb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gt2pxuihlho.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gt2zecimweg.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gt2lurjzfej.html

[R67] 生成随机十六进制串
来源：http://dali.gaohongyu789.top/Article/details/gt2pcztcxua.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gt2lfhgnmpk.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gt2zjpvanky.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbalnsko.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlyattfk.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gt2ejhadgsz.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gt2gibldzxg.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gt2hgdedcgx.html

[R71] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2phgbkmef.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gt2hofbiysy.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gt2jyhfvcaq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2yxxzneuv.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gt2xpzwvync.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gt2joqrrqez.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gt2hrvuegfh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2alywkerd.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gt2mstmkcoy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvjsymvm.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gt2dhltvdgg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2wpmcuftk.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gt2umynxnsf.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gt2xkzhpjru.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gt2jmcjozqf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gt2wmzbbgts.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gt2ngemtgnn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gt2wypszyte.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gt2cnhtzgdy.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gt2oisyoutf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2tdryinxu.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gt2arxxfurl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ctcrbwta.html

[S01] C：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2iozefads.html

#include <stdio.h>
来源：http://dali.feifeiyinyue.top/Article/details/gt2htljecko.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gt2cziuzvif.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2nlzmrrcs.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gt2woswiqag.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gt2pqixrnml.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gt2rbtzifzk.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gt2zqzpbych.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2xfbmrhrx.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gt2chhbqtll.html

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2xvksnynq.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2kukuypfw.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gt2nfpbagvd.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccovslgv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gt2jcjtsxsv.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gt2vxbvfjfk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gt2wbpnojxa.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gt2wtpclxzx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gt2thgqlxks.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gt2hwlywzge.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gt2yqrfedie.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2bjusdohh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gt2foebzhzh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gt2xejjljdl.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2thbeubui.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gt2djvthrsm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2rqeigmzd.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gt2nshjietm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gt2ydfqabix.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gt2oakqyzpm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gt2txrhgdgc.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gt2wuwanmva.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gt2onrpkier.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gt2zrefvnmb.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gt2tmhnnpkx.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2rnfptwth.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gt2oblkilbp.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gt2jvtzjtye.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gt2uerbcwrw.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gt2iytycyoq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gt2nyoajigr.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gt2cymfkqkw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2jgwlcdhz.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gt2feowgynh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2lirgodhc.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gt2cnrwqowo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gt2gxxjbsma.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gt2rgyerhyn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikenbevd.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gt2eptvgzaa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gt2peivlrir.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gt2stakldxl.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gt2esgffukv.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gt2ppfwmmjw.html


<!-- 参考信息 -->