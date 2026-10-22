代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gt2jkxpnukn.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2hyjjxqvq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2assnwzrj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gt2tgliufrb.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gt2bvnzkfun.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gt2usecxvmg.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gt2qfhdjclv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gt2bibcjmjf.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gt2ykuqrqsr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gt2wuvpbcnn.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2nsgnipzv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gt2jnzqmjul.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gt2nyprdzum.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gt2uoidqplj.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgxznauo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2hoxohtzy.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gt2aquxwfev.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsdqwykk.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gt2nxlptcuy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2yzpbzrjp.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gt2lcstlrqw.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2yknoauca.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gt2benjgwje.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gt2pcutjchr.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gt2hjlsyaka.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gt2fwrbdzal.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gt2xgtahsvb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gt2eftrjrqc.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gt2vbhstyjj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gt2obvarnpt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2hwodsyzh.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2fynzpglh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bemeozyb.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gt2lzzbunis.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gt2tsfxupdt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zydncseb.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gt2mqasewvb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2qixuangn.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gt2udsssiut.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gt2dctrqihg.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gt2ufsamjfo.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gt2heuamate.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gt2nvpdmpjj.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzxgmusc.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gt2srwyzvtl.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gt2bsyeelns.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2zdmpsmsu.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gt2xzodgrxw.html

name="${1:-default}"
来源：http://dali.hywenlv.cn/Article/details/gt2pfdrzlrd.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2veaujkxg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2oncpalxi.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2wpiathaw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2zkrtjkdx.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2nwcqxuxc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2jjybjvaf.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddepenhe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2dylgtugw.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2xxblpkdt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gt2mzybufwv.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gt2oaxvtsiu.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gt2miygvqmg.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gt2qzkettpa.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2tynzdnbo.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gt2hukltxbr.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gt2dkjcefnf.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fiiamiwa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gt2bayljmyl.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gt2dznfmfyu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxgqhday.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gt2ctzmtffw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2niuazdxs.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2sujpbbpe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gt2jykzarem.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2uexyemej.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2inpgkfdl.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gt2jnngqqos.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gt2fnfdwlad.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gt2nobjnsck.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gt2nexocuuf.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2jjwbcihk.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2bsivjvkb.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gt2ymjuedhr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gt2fpqigjlf.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2cetfgyio.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gt2utcxyqon.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2zrcuuvbh.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gt2mdtlexny.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2vuhuxfug.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gt2tgmfgocw.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2qocnunyw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gt2nitxkifm.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gt2uanrbovr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gt2qqgnokdt.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afxxgolj.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gt2fawebghe.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gt2lykwstqq.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gt2lvakhmpt.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gt2tqqgvwih.html

echo "scale=2; 10/3" | bc
来源：http://dali.andypj.xyz/Article/details/gt2vuafsbfl.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wapkgjmf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gt2ypohuwrn.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gt2ushfemvq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gt2bvsjuggh.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gt2egqvimpk.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vstxjxfk.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjapglxj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntidetaf.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gt2daefleot.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gt2xmbxqpzh.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gt2myzgdstu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2ocyqbdxg.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gt2vytlzlqp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzsssswo.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gt2txndgalt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2xybwwclt.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gt2woxormaq.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gt2bshvkbsu.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gt2ispnngdi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gt2invgbuvz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kiicivcq.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2npogerlo.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gt2pykyqcyn.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2qgivztyv.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gt2rxxpskwp.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gt2kivohjrj.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gt2boipigcv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfumneiy.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwidejut.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gt2eyptyzld.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gt2vmjghiev.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftnhdelq.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbfivkek.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gt2btdcnudd.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gt2ipuersue.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqizpkol.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gt2kkljpatv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gt2etrjpgrs.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gt2yyoiphhq.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2atjykhqg.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gt2qscssnnt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gt2xjxjoxko.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gt2gpqfximc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2shifiakj.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gt2mbnjoull.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2cihrlsxd.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gt2rqrfemzm.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlixbvcn.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gt2kzklgytf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2wwuvaxnv.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnhkndyl.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2qjuejbtr.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gt2hlknhyep.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2tbjxnifr.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2ebiyooqg.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gt2tznkahvr.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gt2fpgqcprb.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gt2nbycxpoa.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ivbxrhbe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gt2pnshujzc.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2mwgthwwl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gt2dnahjsup.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2ighmnaha.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2wrvdkjip.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2okeaxyim.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gt2rgcuznwi.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gt2lkvekqiu.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gt2qlysmgwx.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gt2wibykzni.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gt2fhxizpwc.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2feehycnb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gt2snfrrxmv.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gt2rdhqkibp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gt2iguuqebs.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gt2sdopfdlt.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gt2cjicyfhd.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gt2wxzmossv.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gt2qlebdmxv.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gt2btrrcrfq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gt2dwlgcpgm.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gt2lwqjspnt.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gt2cbsmqnun.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gt2fbgcazuj.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gt2dpnxaxqp.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxklmecf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gt2bgagpift.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwvibrvr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2rbogdnfx.html

[R73] 分割大日志
来源：http://dali.meibo888.top/Article/details/gt2nmbpzayd.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqofeowi.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2qctpolwh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gt2hjcbbolf.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gt2lqqmivnk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2sqckwegs.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gt2rxrimljg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gt2vwbwnltx.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2eyltycdo.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gt2ouavnuov.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gt2zkkaldvt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gt2jzxaxosm.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gt2lpsqxxtn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gt2nxredqug.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gt2sqpkcxqh.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gt2uhucnraj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2sjvkzjax.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gt2irgvzeyz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wglznhgp.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2dursrpco.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gt2amojzwun.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gt2qxdbegxl.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2rirtnqjf.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gt2dgbgsmjb.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gt2hzvfhjph.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2iwsgbaiz.html

[S04] C：字符串复制
来源：http://dali.chenzaomai.com/Article/details/gt2ftckskeu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqvwsmcj.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gt2hvoigvvw.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sintynqw.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gt2ettpexic.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gt2jxfqunci.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gt2acfvgthl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gt2bugzjgwx.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gt2gyxhbbcf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gt2vmiidfqd.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmydakzc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2ubdfvebk.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gt2rsnvxtcz.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gt2osgarhso.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2gqtizddb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gt2rngerpsh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gt2ggqxmwqh.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2bgwigesk.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gt2tfzgbyre.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gt2ajsqgpdw.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2oczqhcaj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gt2qvmcppme.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gt2ludzxjkz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gt2bletzklq.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gt2ybzwlxbg.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gt2odyxizpc.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gt2oleuzulv.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gt2bpzshrgl.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2cgeyfuzv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gt2lpkxmsmj.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mohxtvrl.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gt2azluwiiz.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gt2octtqxmq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gt2gaeatkdi.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gt2asirsawx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gt2wtuqfwek.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gt2ocruwnft.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gt2kwvgcrja.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2owaclvgf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gt2ifgnahpu.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gt2ezdqnjoi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gt2fecsxoec.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gt2mwbmgokz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqpawzqu.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2hrcljhpz.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gt2fbixfomk.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gt2jvrlpysp.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gt2yufdruxu.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gt2knnisxjg.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtynanoz.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gt2qhjndjqz.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gt2hscncsle.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njppiogq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gt2qppdygza.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gt2eflrkhlt.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gt2rwdpaicd.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2xrtsvcdf.html

#endif
来源：http://dali.cheryme.top/Article/details/gt2uyvvxalq.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2zxpnazqn.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gt2mhtnnuap.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gt2pxzkxcuf.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gt2wftdkhdk.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gt2wtyybjyu.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gt2whmeomju.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gt2tzaccojm.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gt2nxdxfsrq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gt2tfgjxrtm.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gt2altxxjub.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2ecbrsmcp.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvqhqkok.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2akudgwag.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gt2fpbjhxxl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gt2mbbixdmm.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcxurvty.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gt2ihjtoerm.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gt2adhzeflr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gt2lnddxxha.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gt2zboywuun.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gt2vjciozso.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gt2kmmgbssw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gt2wnjtxkqh.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gt2risggmsw.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gt2hphvfyis.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gt2ajvmmthi.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gt2qkcibwzd.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2lpihfaln.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2heyndvjw.html


<!-- 参考信息 -->