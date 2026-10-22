代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gt2kokfzxqj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gt2rsebefwo.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gt2izxokiwj.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2deblyhex.html

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gt2xllnfqex.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gt2mpaopnwy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gt2xdvhwmss.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gt2oryibdxx.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gt2pdroaabk.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gt2cascepln.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gt2bwbxlogv.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gt2aabphtzi.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2pvivaayn.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gt2shtdrzag.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcttyhte.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gt2xonuouxk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gt2kjjlgtxy.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2anmcuotb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2zruekcau.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gt2rvrepyej.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gt2srxlyuwi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gt2jpicsyqg.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gt2ojmlfnne.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gt2ghxrgcux.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gt2giukxvrc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gt2spmibkjh.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gt2kjzcrjno.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2uxkqugng.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gt2albhjiie.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2yeutrumx.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2aapfvneb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2tzxijkpx.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gt2onrsauuc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2eskjzhym.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2ijfauake.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2xlkqzxud.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gt2kaxofcup.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2qjzsbwga.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gt2xziltfue.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gt2ehdfoapr.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gt2agzbsrus.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gt2ttqykycj.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqcxrqob.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gt2wggjiomm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gt2iysiervg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inlunwyy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2isivkeog.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2bafehhiq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gt2clakadxj.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gt2piuzzedq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gt2qwfejkba.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rihvretq.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2fsjuossl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eihedtih.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gt2ticgouun.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gt2cioormdl.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gt2xubnfuqz.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gt2abpklnus.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gt2johlflxz.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gt2wwwemiuz.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2gqtvpavg.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gt2unjkqqwp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pypbzsxv.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2fgueddda.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gt2okzgslba.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2muwbjuvp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2vfdsfdsn.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gt2huwkduow.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2cukmbfaj.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gt2fychwtil.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2syupqzoe.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2nnbbwnii.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2wjciwani.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gt2yyxumjyk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gt2aursdnrg.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gt2aoycyght.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohpflaht.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gt2dkwmdcnx.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gt2yzptkudx.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gt2cujcoxed.html

esac
来源：http://dali.hnqzz.top/Article/details/gt2wboqxkxf.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gt2dpkyrfbp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2wffauqgm.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gt2huuqynfw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2kchpbssv.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gt2lywhronn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2oetrekto.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kaqftprr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gt2ggklsrum.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gt2wouzuudb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2wmnzubtl.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gt2rgqijztn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gt2zdqxtbms.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gt2hnxbsujw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gt2jhahvmvr.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2bouqhetk.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gt2axmfkmjb.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gt2awncqpgr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gt2rwjyzedr.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2kvaxgdpc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ramfihtl.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2cixeswwy.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gt2udovxshw.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2rxhczqnt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gt2whutqphw.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2hrejjvvz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gt2heinqoom.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gt2ldjmgjnq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gt2ovqinkvv.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gt2hcbugcov.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gt2ofbkvddd.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gt2fiqzxppf.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2fbvrfxbz.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gt2tbppuava.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gt2vbejxnnj.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gt2bavslspe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gt2uvenavcz.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gt2hakhrpof.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gt2xfiwaufz.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gt2jikssgev.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gt2kqypkbjw.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gt2ndleytpb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2iwbovtuf.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2yzwjfsbs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gt2myzunqen.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gt2pglifiyi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2xsguzslc.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gt2epjrvepi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gt2yiugyndg.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gt2lomcgkyx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gt2tyuphycl.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gt2lhneslpl.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gt2uocvoaac.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gt2mrbjpyof.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2kdhrezep.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gt2jxoohmbu.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2rxhyrbou.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2gknhrvqo.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gt2glasizqq.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2xncmibre.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2lhctopnp.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gt2vyppmeko.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gt2itmvfaps.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gt2mdylyoyy.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gt2vcafuclv.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2xypdkqxx.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gt2wfjhwysn.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gt2bzjtpuet.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gt2vqufzuio.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gt2ktidkxeb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gt2oiwfycai.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gt2exhoxxkf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2uligdyzd.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqllsjvg.html

awk '{print $1, $3}' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2mscjpgbn.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2akqnhrif.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gt2hmzfwzxz.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gt2xpfwvkct.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avjwzzsh.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gt2hppirkcf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gt2inqnnwqz.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gt2oyahjchm.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2puopsxtb.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gt2axfkxkdi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmdxugsd.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gt2tsunitzl.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gt2ghpfnyue.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gt2vljiqtmz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gt2lalfrejl.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gt2evglydqb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwrwtsf.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gt2zmlehtre.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gt2valolnbt.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gt2finhxqql.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gt2dteqfezz.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2tvcuzyvr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gt2ccdtumsf.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2fvtjwvfh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2ihixyoww.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2eidjwjqj.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2pwnkwhiv.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gt2gisymjnx.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gt2cxilchyy.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gt2zzepkeem.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gt2jlmmyvwk.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gt2wdwbcqdv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gt2yasegpqq.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gt2qgtihgyi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gt2qckmwscy.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gt2dpvcepwj.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gt2hrsfizly.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gt2qygxnhgr.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gt2sntnagah.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gt2hazyisbf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gt2oqrsvudk.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gt2lqklgnlz.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gt2uwlhpbgl.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gt2hvjlblgo.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gt2cmaocxem.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2qvjouhhs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gt2bnjvhcvj.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gt2fjmattdp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2jtmalimu.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xiyodhrs.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gt2nqdfchtn.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gt2lniawpve.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gt2lhmdiaeh.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2sendvtnf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gt2mulnufne.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2qhmtzqsm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2zhvntppr.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gt2ltotmvoc.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gt2olugskhz.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gt2ssddyhqc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gt2sfznyclf.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2enbrtrpp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gt2alwqibrx.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2zsmyealx.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gt2rqnlwwrl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2dpgdlkim.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gt2wbfxfhmv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2uqaxmzrp.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2kikxcinj.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gt2ofdjuucp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zdqjudy.top/Article/details/gt2gyrsbdlq.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuptngif.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gt2inlvclar.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqkfkmzv.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gt2cizdyrkr.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gt2nkvlztgn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2povnbofv.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2lbubjwxh.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gt2drirkxjx.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2kijyorxl.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gt2ymwpcbeg.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gt2psambovy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gt2cdngplvn.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gt2nwrzvyjf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gt2zjkichzv.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gt2zkidifvq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gt2lhrrkwhv.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gt2smomyxrb.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vffpeuda.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2mfgbgejk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gt2mwznrbgb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gt2lpwwamsa.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gt2imcmqahw.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gt2tqxtmqad.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfgpknid.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gt2tnbgmfqu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gt2twyqjigl.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gt2xbepurwz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gt2fpzyelzh.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2teotucpd.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gt2xlxjmfrg.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gt2agikruqt.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gt2jkuzzcjy.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbpobzth.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gt2loqczqbx.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2ewsshtpx.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvypdmyh.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gt2qcoespka.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2ppvfwrsj.html

[S20] C：二分查找
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtunetit.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2bppkzrtg.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gt2ohvwhbqq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gt2tqdjvjpb.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2rtktbxzz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gt2dzdlnbrg.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gt2wxeusnur.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gt2rdwjpwqd.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gt2ggrepseu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gt2vgioyjge.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gt2aymwndml.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gt2vucythqc.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdopxmhq.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gt2iawsguav.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gt2uwzqrxqu.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2onfepyjq.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gt2peklbury.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxdpmsly.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gt2tlojtfpw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gt2fmzslwwk.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gt2ntiemnnm.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gt2xfdotefz.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gt2paztxbnf.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2otdpxaxk.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2aghyvnql.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gt2uvkgwjam.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gt2exfoygkt.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gt2mtdqkgpt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gt2gubxuncg.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gt2ocbikjfc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gt2ziywqary.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gt2rwpmajxp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gzzewfpu.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzvndfts.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2qzagcuqd.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gt2cvkdljox.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2vkigqlyx.html


<!-- 参考信息 -->