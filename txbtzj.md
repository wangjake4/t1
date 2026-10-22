代发 wailian999

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gt2yahdovoo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gt2jsggowlw.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gt2tvnmbzot.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gt2rgrsckil.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gt2hxejplzl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2tduiizyb.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gt2omdlhjuz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzwnebau.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gt2clvlrdol.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2cianqduq.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrzarevp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gt2etpdrizs.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gt2bfreywni.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2owdigttu.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gt2qagbkaud.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2wuimkvug.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gt2ggzengan.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2sbhxyqon.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2bksmoaum.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybwjxroo.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gt2ynkzhstc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdtnifzm.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gt2hxtqczfr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cirwakld.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gt2yptjgsif.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gt2dimbzeuv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2jmvfigmh.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2hfntjsbf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gt2dtfmtrxe.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gt2fddvxelg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gt2aycbpohf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2sjpvtkrh.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gt2rcclnsew.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwapsetq.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gt2cpyczgfy.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gt2jsysqxbg.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gt2qlxbqtjq.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbyyhsmi.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gt2vgndaedj.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2ucrraxaj.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gt2pvqulscm.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2esbyvdpt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gt2vvtgmyzq.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftlkhpin.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gt2pgepjorz.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2yonxebkd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2mmhrbssq.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2wukhzcmh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2ycjkxozo.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gt2btvvsblt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2yenlwmtv.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gt2yutqegbl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2zyqiiomj.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gt2vtmgvnnn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2fnplikhm.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gt2sjwiggpt.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gt2jndifrzl.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gt2qcthmucl.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2rbocjdnx.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2bwbjcqjy.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2vgcehfcq.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gt2tftxyvpa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhkstjch.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gt2fltkgdny.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2vfgwxsns.html

[R14] C 风格 for
来源：http://dali.hnxiangtu.top/Article/details/gt2zcnzubze.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2wcqgjfpk.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2eamrasbh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gt2hxvtpbni.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gt2hvohhjig.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2zpndjuou.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gt2kselbkos.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gt2wrllmbhp.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcmoyoyx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gt2jlhhnkek.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gt2nwlvddpw.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gt2tpfpvrjn.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2arrssmtu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idtawkpw.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2pnflsrkq.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gt2awcjvrtq.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gt2jvmxkpie.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjcfzlop.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2aliickgv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gt2qyohirdg.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2noumvqcc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gt2wibykblq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gt2qcgfroqv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gt2uymaonin.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsgcjrvi.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khtvruba.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gt2zbfneatm.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gt2ggqwjyhf.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gt2bevggffe.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gt2kejzyury.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2vrxrihza.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gt2uvjikzyc.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2ndpffqry.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gt2gmztytvu.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gt2fbrqivdq.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2juobfajg.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybatousz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2nevisnhb.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gt2borbavhb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpreivst.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gt2dcbqtcqd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gt2tcyqygzp.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gt2edyzpitz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gt2aywohwwy.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gt2mxcrmkki.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwgclxxz.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gt2xhtmwaay.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gt2okmtkjlt.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2ghhzofau.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gt2mywwbtgy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pimxbjkp.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gt2bgjkbwmi.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gt2dygaaplb.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gt2bwwyvpxh.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gt2brgxdnln.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gt2ttljpldq.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gt2cdfcxvat.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2mvytdusp.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gt2urtrfvpc.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gt2xxkbpzst.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2rpeyyiod.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2dicotgrq.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gt2nnzbvjwg.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gt2szogqild.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gt2vzkkcgvf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2cvnnioml.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gt2nomrkpyf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2zunldwjn.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gt2vzamrqth.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2dkyhfzvw.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gt2rpgtcpga.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gt2gzajtxkp.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2mfryqjyy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2gjkhlxrc.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gt2kqagykbq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gt2kgixjyay.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gt2btqzodij.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2ggkytjzx.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gt2ghsptfzv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gt2cecmihyr.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2uhtckehu.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gt2itfoyvxv.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzrerufi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gt2doupyafc.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2jiqxaimb.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gt2uhftpxob.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gt2puizvyct.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gt2kevtlsrm.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gt2jwjpegua.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gt2whchmexh.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2mspfaebe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gt2krqhtsow.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2ibnorepy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gt2itptepzb.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gt2ksuctpul.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gt2jevahjbg.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2awzhcrde.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gt2ueqdmylw.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhgpxudf.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gt2snnzweej.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gt2kyjinwjo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aeistepo.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gt2dxwlxhsi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gt2ltvtdaqt.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gt2bbmyufmt.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gt2hjspvqki.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gt2brcwjfqo.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gt2klwozgmi.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gt2qkpoqngh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gt2kmpuuqpz.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gt2phtljrav.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2stnjfite.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gt2qgrywnby.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gt2klmfrhfa.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2jrtfzgfl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gt2tszxpumj.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gt2agsnbdfw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gt2towzkfcw.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gt2xbendrsa.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gt2zrwfrpgu.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gt2rarwhwig.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gt2bygsgets.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2aqwdibua.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gt2mbramfcf.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gt2tfkshwim.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvrikgjw.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gt2znopgkvd.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gt2xyuujbtr.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gt2gpdclzmg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gt2zybggcaj.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gt2lqjxwfdi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gt2yzkleevr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmonmloj.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gt2gvoxozbs.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dkbiwfpb.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvbzpodm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2theafgat.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2jndhqfdg.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gt2sizzwiwp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gt2oprzujdx.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pydnxvpx.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gt2dvzqbnxe.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gt2dxaoksiy.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gt2kaoxloey.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2nubxudkn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gt2mjxaoeji.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2bkftdgfw.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gt2swychutl.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwnzbmpn.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gt2mahgxwyt.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gt2iqoaiecm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gt2pvjkgicl.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2uzrxofmn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gt2ubdkavzd.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2euzurltn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gt2abawqnmj.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gt2bjpxhrgk.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gt2rwxfczgt.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2evjbuirh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gt2uowmhltu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gt2jimuqabo.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2lqkyctqh.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2vaiadqji.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2unhratsx.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gt2urzsmhbs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gt2eskzsdnz.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2rzfkukus.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2iybyzmay.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gt2rdjkywvi.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gt2skqrwyzx.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gt2ntyaqqkw.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gt2onfngrkz.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2pgztmzvk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gt2drqvwtzt.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gt2ptgvvgcm.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gt2mhkvlavw.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2djzqrclj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2jwlwgkql.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2ipefgxzk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2aqzawrvg.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2qahvtjmx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gt2mtzksjoh.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gt2vkujahrk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gt2umsdosxx.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxsjuwov.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2sbfjxmse.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gt2mtdxndpi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gt2pahjpqdx.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gt2wtanlhjk.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gt2snwefutp.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gt2pmkvjiui.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gt2opifggbp.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gt2iqvehzlh.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2rfknzydm.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2offovdqr.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gt2byvifrap.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xeklrxrj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtxoklsb.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouhygucp.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gt2cqiljqkb.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2gufasalg.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gt2wejliywj.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2wesxqair.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gt2wvcofepg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gt2cdjinhru.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gt2qirufnwh.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gt2ixzmezgq.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gt2nbvissfr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpvtenxx.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gt2ejlketob.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gt2sqzpjcnn.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gt2sshuyzqm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2pwifcgsx.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gt2yadmxsey.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2nnbqxkry.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubgijnbm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2aymttbca.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gt2ysnqnwxt.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gt2foksruph.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gt2uldzdswl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2vhfmxdhm.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gt2tmtbkqak.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gt2irznwgaw.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2qmybqkcv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gt2xmqahbpx.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gt2vruynadm.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gt2haalklol.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlgjouxt.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gt2gudqsivi.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gt2maeqpjal.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bessujyz.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gt2yawzhznu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2sdaioohz.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gt2lqhgfmey.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gt2rvpvhwxe.html


<!-- 参考信息 -->