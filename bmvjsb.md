代发 wailian999

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtfrhbngvu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtiynnltfv.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gtyjzskpcz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gtwuvzaxbf.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtflpckclu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtiakocyto.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtyrpkbqhz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gtgkjsgyak.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilppoojq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtmkcybyzx.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtsgijuswg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gtwxdftrta.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtrnurpsdn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtrivcwmaz.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtqbvgvhez.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtemdbgehb.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gticgxvuec.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtlncxgobx.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gtgqyyiloj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gtgwftkzca.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnjtyguc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiydmlrnh.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gtpqdiqyil.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyihvqmrd.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtwotjumcz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gtmgavdafl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtuxvywafc.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gtbqjkimax.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtxdczjlde.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtzjmkieqa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtlcwnoedq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdidntjvn.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gtkukodrhu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtufttmhmx.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtqwvjotge.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gtbnfrlmez.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gtmkuigolh.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gtrfejrwqr.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gtibeifjxw.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtzdsimjie.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtvpqfcmmz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtwpkiabel.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwswadxnd.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtwatpocwe.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenojkplj.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gtjhdmxkfz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtgxryzdrq.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxqcmnqkv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtuagijvra.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gttfgudqno.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtptmxcsae.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtgosnqwda.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gthrmzzart.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtatrndkmq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtfvnadrbi.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gtmvqrfhwf.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gtmfogpnrp.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gthinvqcda.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gtlfzzdlrb.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtmkcyyble.html

esac
来源：http://dali.meibo888.top/Article/details/gtrwivugcd.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtwlprlzmd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gtuelsokql.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtxgvdzxcb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtjozinhle.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtoiiptocl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtfyrxocfw.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtyrwlhgcl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtifnevvch.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gteapqdmap.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtmsjvfign.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gtyuvnpisb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtyozsuwcm.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtqjhjrkeo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnpjqhaj.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtwphowokk.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtbbizuivd.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gtmpfwatvl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtonsdllwn.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gtzywajcsq.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtlxnzmmpv.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtgmrcostz.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtfahbhvvp.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtcptchtyg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtdsqkupnx.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtnvxrpofo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtsfgkywhh.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtoplkhcuo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtwggnohpo.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtloakaefd.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gthnhnkrez.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtcjbphqhm.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtpazmaxtv.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtruyrpphd.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gtwtrfzpkr.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtagirbvae.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtszuuymdz.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtwwgagdxt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsrmfkyk.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtfegijzix.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtxcanfbdf.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtchtfgaab.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtsmfhrdzh.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gtnmwgwcty.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtfilrrgfg.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gtwvinaoym.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtqrvzwane.html

[R35] 后台执行并等待
来源：http://dali.gotoacloud.top/Article/details/gtauylytwz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jyoumei.cn/Article/details/gtwbfaevea.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtqnzgtmqe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtxrtvgsfh.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gthqlisneo.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gtapnuxupl.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtzzzhspka.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtjocvuewa.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gtlqvkgthy.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtmempluez.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjrutuod.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtlslhhsnl.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gtyatepbae.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gthymxeqrp.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gtyvntqzau.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtauzqesal.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gtnohqdsql.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gttlqkdbpd.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtrffvpksj.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtzvwuwfge.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtrvyjjzkx.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtbrcdhggf.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorcztcra.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtaehhyraa.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtuuwvcknm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtttmsxete.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gtwfhctbyd.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuioteivo.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrqceslj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gtqjdhxvgg.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gtfjdhreff.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtothuvnxz.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtdywnruqt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gtytvvmjqq.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtlaxnzjai.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtuubufvvh.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjmcivyj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtnhhzmnrx.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gtbcviuvis.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtsawczgmu.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gtrgbwrpcw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtitrcujgi.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtncvrjtyi.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtunklywks.html

[R57] 远程执行命令
来源：http://dali.yj20258888.top/Article/details/gtubetckaz.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gtbbpcyezq.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gttlkqsdbb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtjswdnnoi.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtgqeedugh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrummkor.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdudxalx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtdofphllf.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gtqmhjhfnf.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtnmnlzbko.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gtyzlsjuty.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtrrmmuzvg.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtbrhtssoh.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtffqboqig.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtdxtukkph.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnjgfzij.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gtlbvzgvcf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtzixjqjsu.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gtliqhtwvq.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gtkaszgccd.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gtwiobvxqs.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtgobofgke.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtzytnrmxb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtaqnvgwal.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtkqzhvpbv.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtyncbpnub.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtkzwfvkii.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gtkpmpraeo.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtdvlxqlsv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gtcjcpluhb.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtpxtkukyx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtnnreemzc.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtdaeqgicz.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gtxgiuliow.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtsrmzmuxx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gtlzhfzzyd.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtfppokufq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtxxacdmen.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtnbnodpav.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtfxhnvyfu.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtkzllvtje.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtcjzlefug.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliiujzsa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gteafaxnjg.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtcipqbfqy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtbnllkils.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtbpoxydck.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtyakyinzv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthygijivy.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtrkrpztot.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthxedwuqf.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtjkctcwin.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtxumojxse.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gtpuvawmzf.html

[S02] C：变量与格式化输出
来源：http://dali.ydzc1.top/Article/details/gtoaduyulk.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtglglmexw.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gtoabzezyn.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtpvuqrnpt.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gtwkwitqse.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtqorozlkt.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtzbmvaucd.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtxuvmkmsc.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtesawkpxx.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtjoplykqt.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gthwwgabkh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsecmslhj.html

[S08] C：动态内存分配与释放
来源：http://dali.chenjidiqi.icu/Article/details/gtfgakmptw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gttcsqybwk.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtzkapmved.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtvymhggxp.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtkolukkpf.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtjjplfjyx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtgktncbpl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gtyloazfrg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtwqdggtxd.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwrlpmge.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gtovwkpwpm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gthgwqgzay.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtudrmftmi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gtqtajjcgh.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtuyiquuov.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtoqliqqcx.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gthrmmvyzj.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtjtwbdzba.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvgdevbx.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtedssfkaf.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtelixuobe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtftvjnjyw.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtyvpojrow.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtquaenbhx.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtvnffhrcm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjymqyuxd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtispokase.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtevaxfktq.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtewgzlttb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtjdciiibv.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtlwyyzwex.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtsspwibup.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtxjaevrxs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtxpxqswma.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gtkwqujdkn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gtbkvpidsk.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gtbexjjodc.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gtczdacham.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtcxjqipqt.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtkcivzmrn.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtvcqgnftr.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtelfedqgm.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtvheigjtf.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gthhzconez.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtcxyrywnl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtekeudvee.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtmfyvnqxv.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtjfggzmaa.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gtkkgekjjv.html

#endif
来源：http://dali.jianghu66.top/Article/details/gteqolxrco.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtbdnlutil.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gtvokdwavb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtmmehrowj.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gtbcjefeyt.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtjbmjucrj.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtocpjftqn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtozcdrqyc.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gtetcihgek.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtqgfeblnu.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gtljwouchb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtsmsslnmh.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gtaomvaquc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtwuseieik.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwfbxrxk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gtqwscifxb.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gtsjiawmkt.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtsezsxpud.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtepzghuja.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtgimpjyvr.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtcefxltyi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtguvcnhcj.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtvzxnxriu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtqcijrgds.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtlarshhas.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtuaerxzcr.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtrdycbmlo.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtxawpqhzq.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gtfgpclesb.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gthkoatcml.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtgvovyvut.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gtlyoezucs.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gteyudwtwc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoettrtyj.html


<!-- 参考信息 -->