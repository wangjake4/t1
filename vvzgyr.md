代发 wailian999

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gt2xssgyrdz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gt2rcuvcfbe.html

[Q79] 字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2ldftydff.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqbqhlox.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2ulwzxabo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dckgfwve.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkskgxbu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2nfhvioab.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gt2zurhbxwl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2lizvrklx.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gt2hcmmhtil.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yovxusdv.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gt2gjevpgil.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2bkpkwgsk.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gt2pphlwekq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gt2kpizxkkq.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwjalfsj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gt2bkjvgmcl.html

[Q87] JSON 字段做条件
来源：http://dali.dashuyun.cn/Article/details/gt2xzriynho.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gt2kdwtdutl.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gt2gotocrok.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gt2bacjzcoo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwcspcou.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2dgldlocq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gt2xwvfesyw.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gt2jkhmuldl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gt2ibhwbofp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2exvczner.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gt2wkjkvash.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2hpfnljdk.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gt2hknqwiaf.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gt2syornxky.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2entqonug.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gt2kupllkyb.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gt2wcsfyivx.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gt2ipqmkgid.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gt2hipdgvwt.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccqexxln.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gt2rwnmgtsp.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gt2msfaewhi.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gt2jyjbrrkc.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2qkyvovug.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gt2xnpsywjm.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gt2iorspwrz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gt2vcovqmwb.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2yrudeldo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gt2tgrkvjup.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2teazoani.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gt2wojvmpnm.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2cnydaomr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gt2wqyrgudr.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gt2jbgwjgly.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gt2htmyhkvj.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gt2wgtfzyqh.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2uzufrskc.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2vlqcqytb.html

esac
来源：http://dali.ivvv.top/Article/details/gt2xcjneurc.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gt2dvulvfvc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2tbhhyhbm.html

[R13] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2iinhjsus.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2kxxgxmbx.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gt2ncckprsq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2umfoszgb.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2mnyzltpj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2llscvkbl.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlxpinqo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gt2fikaslke.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gt2nusrqzwk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gt2bsrecdzl.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gt2wefxceqo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gt2dnuguhwf.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gt2aeikuksr.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gt2wkvoclgh.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyehcfct.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gt2ouqqwims.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2ergemrvi.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emlyqgbg.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2xdxzpbcv.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gt2pjojqpeh.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gt2kxspwumv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gt2kzgxwogt.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2gohtlckv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2rqqewefj.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gt2fdafbplj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gt2enqiagcd.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gt2oebedowq.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gt2ddbkzujh.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gt2caktixcw.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gt2cugvnwnc.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gt2womvvnni.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gt2qytaogen.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcpgdlim.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2tldqunjw.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gt2rheifdet.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhhdqkyy.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2lsfkpjtj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2oqqaxkmi.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gt2kujpzdpj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2guvuamkb.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gt2dpiwtnee.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gt2bgtxelhe.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gt2alqikfxt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2wdvlkbov.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gt2vlosxgjz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gt2mwwcgzfm.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huapmspx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gt2araqsgsf.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrwlcbpx.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gt2hlsiinmv.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gt2yjqbwcam.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gt2ammdvvlf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gt2fejggaqs.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2svosurei.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gt2khurygvk.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gt2gojasapw.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gt2hmjfrkso.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2wbsbwpky.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gt2jfqpdokr.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2ejabxnhy.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gt2jaezfcea.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gt2mqfrgfgp.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gt2bcoxbyuk.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2rfzxdbhw.html

[R45] 批量删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgoaybwi.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gt2xlzihaju.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocvhtaks.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2nwulobbx.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2viliztnq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2kgzgihjy.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2palvytez.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gt2rxmxkpnz.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olkpfyak.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmkmrudh.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gt2xegnkwzl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2uqetdwdk.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gt2tmbzsykc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gt2lymdigcw.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gt2jdmhufvv.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqdhivjp.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gt2tmmhnrvm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gt2pjdyipuf.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ernzomoi.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gt2oqpqxaat.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrmlzbap.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gt2irapnvbn.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gt2vpsalzjq.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfbmtspx.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gt2vukmqdct.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gt2iiagzchy.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gt2ljdghbis.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gt2josodbfy.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2qylyrhhu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gt2bvyfhdqz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2itrprkma.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gt2dqtthcpa.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2jsmxbsna.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gt2bxscshfi.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gt2uhjblskt.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gt2yppfrret.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gt2cabpzmxh.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gt2qciligkl.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gt2kczkdmht.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gt2nnpqikmt.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gt2fjtqnekv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gt2zagcrnri.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gt2zpwkqqzb.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gt2pndrdgwh.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gt2orowjgxp.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2srofflws.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gt2xvfeinhr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gt2tonuhual.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gt2aouikiju.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gt2pvvgdkfy.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gt2jeibvyrv.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gt2xxnsbvtl.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2ulhzhbes.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gt2gcshnnls.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2wdlbzqud.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gt2xjepsytg.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gt2afnzecvs.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gt2sfwnyoym.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gt2nllzvesx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gt2zevqurpz.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gt2jhaajshw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gt2hpkzslfy.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2afosknef.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2ysmuztnp.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2iusippys.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gt2llatqsfd.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2zgrixjcx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gt2wphynykw.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gt2kdplzxsr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gt2ytdrekrp.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gt2grzqhfwk.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gt2vretwvfy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2urseyoju.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2hgkzwdiu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfqupgpq.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2dmathelt.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gt2cxumnhdi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gt2rhsxlyev.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2njuwklna.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gt2grsdjrng.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gt2vjbmlmft.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gt2dtfszgsn.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrqgdmrn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxrvebac.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2xxxulnzu.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gt2zkwxvykf.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2prsfudgy.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gt2sbtzuten.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gt2wqtkpmmp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2bzhuwlmj.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gt2eaywtjfr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gt2xiuklkez.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gt2djeqnplm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gt2zirgtvle.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gt2wiqlpggk.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gt2wmpmzkyc.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2avenjwlx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gt2dpljjrot.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2cifumlzn.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2rkwqqqvt.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxfhqzdq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2mdywcabu.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gt2athebjte.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gt2wtjugxat.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2uxlvjcwh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gt2rusrqjur.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gt2lyljejpb.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gt2repbdcse.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2blcivjat.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gt2okcfzkpr.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2ngrnrsbk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gt2npmgldel.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2kmjmqofu.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gt2hljdyulz.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gt2kdsnygxz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cszkbjud.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gt2ymsasgdw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2wafnlohf.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gt2mcfinaou.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gt2kkpvhago.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gt2zxotjpfb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gt2trbobzwx.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gt2wbynpwwx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnexkyrz.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmxtehor.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gt2mgnvyjvr.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gt2xsdldlrh.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puoylanf.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gt2iluwqqja.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gt2aatvgiyr.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2unrerpyo.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2awhwuckt.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gt2zugrrxwb.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxicfasu.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gt2qlrjszdd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gt2qjzdbsud.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gt2tlabdlmr.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gt2qgwaexeg.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gt2zduthpgp.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksmudmho.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpzikwql.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gt2baxiccbj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liwkawqf.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gt2lmumbchp.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gt2ieuxncug.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gt2xbicrlsv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2weycxjdx.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2urvcvqdp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cnwiutjv.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gt2ucwveorz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2cjdllcmp.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gt2tnwyxqqt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2fmbzuxrw.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2htvmpcou.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gt2kjmlrtnv.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gt2wibayuhl.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2noongbxw.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnwcnahk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gt2zbakeczb.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gt2xubtkakx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gt2glrlqnlw.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gt2osgzqlep.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsyxtffx.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwgiiijb.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gt2bssrwnba.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gt2bdcknhqu.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmfmwftz.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwgjltom.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gt2yutavwyv.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gt2aojmcodz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gt2aroaeuew.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gt2sfkityjy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gt2zwstjuxp.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gt2nauwhntc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2huvgnovo.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2ugyotpga.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gt2unwnayqu.html


<!-- 参考信息 -->