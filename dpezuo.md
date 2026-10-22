代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtcyjpegsi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gtqnoxuzal.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtmbkvobjc.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtwysuruks.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gtfivkqnyd.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gtmycnyfkf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gtchlrtctk.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtjwpvbuhl.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtaitjewie.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtpmcjlmay.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gtylvfpuse.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtudbhtfaw.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtvmmrvmeb.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gtzrkbmpgp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsidpicj.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrbbcfaj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtfojjjzch.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtzbuszsxy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtbrsxhosj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hysaishi.cn/Article/details/gtlgqyrzqa.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhnyvxwk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtvlhywtpj.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtrkjyddrx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gtxbsvyccf.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtovvgwgsa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zycfv.cn/Article/details/gtfhsgsgtm.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtitzkimwn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtxrytoinf.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtozsonsuj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtzubhymnf.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtgipsyaik.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtzokzdzrl.html

[Q82] 字符长度与字节长度
来源：http://dali.pycfn.com/Article/details/gtubrtndch.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtmibkzvxh.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtlayvewvr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtssymqyfm.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtbmzmcwnj.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtmwjtluji.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtijtmnjgl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gtmcwevcfq.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gtvfnmijjl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gtxsambxlr.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtzvgyyzvr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gtbmdgerce.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gtiawqvozu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtmdbxmiud.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtwrpkafgd.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtaejqraah.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtwvfvanac.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtxvqrcptx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtaycgsehr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtyiwqozlg.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtivdzgkfw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqwrapitl.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gtexeyaidb.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gtxpmciets.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gttyrhhojm.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gtovuxqtsw.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtogezhqta.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gtolqjhqns.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtfniqzgju.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gtqdjmomcm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtawdrpvtz.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gtbkxklrwj.html

name="${1:-default}"
来源：http://dali.guannengcc.top/Article/details/gtujvrjyrj.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gtnzejkefb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtwtkwmbzm.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtratxrtws.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtkhjiuhlb.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtwtfnbelm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtwtjzxrkw.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtublurdur.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtswconcuc.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtxcinhcon.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gtofjgddps.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtvragxpuf.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrahpmoqi.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtkkmnlmue.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gtpzilugbj.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gtmchyuhcn.html

esac
来源：http://dali.zdqjudy.top/Article/details/gtivgjyyxr.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtoebufhud.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtheseywij.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtueidwhdb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtuxltrfsk.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gtewjordco.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtkgzgmgqu.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtrzbxodmo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtmfjdiugo.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtvpgtpeyi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtgntkymqj.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gtjipjspvz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gtkzlfypps.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtupxyieco.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gtztzlrpmr.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtnfekjqrt.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtpxhnbydo.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gtkkswwawp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gtvoxpyzkw.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtfimsprqn.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gteglprtvu.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtuecxxpiy.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gtjcybqgza.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtmartebgi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtodbiphbk.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtdngnxmbk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtxmjplbgq.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenzaomai.com/Article/details/gtzfmcqqmp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtbrnywzye.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtfthhltjf.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtitlzcwyw.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtmzxsmwdr.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtkwpselsl.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gtgvadseop.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gtowvmcnjl.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtoqpcjyiy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtjvueoljt.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtvwqmytjq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtdkfrbulj.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtzzfbigks.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtkgchayds.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtuprajcpk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopevuotk.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gtitorlfdk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtsctgrwcu.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gtptqxdvib.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtdwwjdphz.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gthfyydvgr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtpsixwzud.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gthzoxngnk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gttshklbyd.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtvvaivmav.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gtembirfoq.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyskpqxbh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtpbytdvuq.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gthweojzvx.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtgrwstrai.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtwnfeigcw.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtxdklkfzx.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gtwdfqkikb.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtogvmskvg.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtkktkiyhs.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtpebppotq.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtyjjvqzjz.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gtdvrgnevi.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtayaxpbqj.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtpakxmuub.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtskvrgxto.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtcmnyjwko.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtqogllfrt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtwkakrqld.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtfgazhzrr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtsjmcyinm.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtzklnmjsu.html

awk '{print $1, $3}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtounkzwpk.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtgijfqqct.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtmqxtkgbx.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtnvodcoin.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtxpetftcf.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtunjcwyfn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtvkpkjptt.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtasnhgppg.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtkkovkeib.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtgrzutzes.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtjwprbufg.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gtpdogmmjj.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gttpzylbtq.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtqnittpcv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtwjtvrtyk.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtumplxlwx.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtgxzkmfqf.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gtwkhcpqdl.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gtcybdolpk.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gtxlakruvk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtejmabsnb.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gthvhqwhew.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtiwzshghe.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtrwvdgo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtsgpmbkhs.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtwvsxlhbw.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtkqhxxutd.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gttcbvbdzi.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gthdjmknth.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtkpgusdnv.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtndphmjuw.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gtnxsrypyi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gtxbrtvtsv.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtuclpetrz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtaimjbroa.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtbefnryzo.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gterekkric.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtfgnorijr.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtgvzlbhou.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtoenzhqrz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtckklfmxe.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtzpybfauk.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtsezykked.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtmqgqsegn.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gtenssgtpe.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtcynjajuq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtdsewkshd.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gtxwfvhpzo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtyriaxtqv.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtmafyjsxx.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkcefjfg.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gttmyansgy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gtzhvkeyms.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gtmhxrhewl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtialqoirg.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtpotrbwoh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtofkpwcrp.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtroqpzjrp.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gteznoqqla.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtoymaccbk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtbqhqpxin.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtmlbgvmij.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtddvgotiq.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtqirimzpz.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtlbwyahzb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwrcmwbxg.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gtaghfahaj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnilahysw.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtrahfmlic.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtmbvsaycv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtlzosbouo.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtkqhhllbg.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gtdrnnkfsh.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtqzylgnfw.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtmsqlcqbm.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtcalywets.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtqgxpsrpz.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtcxqwxksj.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gttkckzazi.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtoldbqejy.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gtbbohyjfi.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtkzsjpeou.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gtbcguoxhf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfzwjoxt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gteiuxybpk.html

[S09] C：结构体定义与初始化
来源：http://dali.ppjwa.cn/Article/details/gtsmvxaney.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gtlixtwszo.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gtkbzkyfpp.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtsfbrpwxr.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtqyvixtym.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtrfjyzcqf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtuugkzywe.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtcobcrxec.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtptvaarzz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtiezpbylr.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gtzwbjelrz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtuwcwcfsh.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtpkzsdelj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtugauwuot.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtbgvprzcb.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gttugmxvaq.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gtwxrntrtj.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtifadvues.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtcsnmkddq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtldhqlauw.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtowbifeoe.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtxejrdgsj.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gtyfpnxnze.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtingnynwz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtuwlnjyey.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtidnlyrij.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylbpequk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gtqjrmdgfd.html

[S22] C：字符串转数字
来源：http://dali.cucudq.cn/Article/details/gtxlywklpw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtuxwvdjik.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtcgoxaniw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtaoekvuko.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsttuqqgh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtzrfkzlrx.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtrpkxipsy.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtgwxzmbyo.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtcctbiyzi.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtoucxirtr.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtnldegatz.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtayvnuxty.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtfeivchal.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtrswvhlwt.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtwryermat.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gteifeifwp.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gtopedqkrz.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtxclrdobz.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtbxcfwfta.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtdspbsbfv.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtqzlumhda.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gthmnatgtm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gthymttint.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtlzogmtrr.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gthmubajnn.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqvyemlz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtrajjwnxi.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtoaeyvkwo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtxoiltmtt.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtmproegrx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gthoehvuex.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gtxrbkxsjr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtvjonzhnb.html


<!-- 参考信息 -->