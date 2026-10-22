代发 wailian999

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtkivlsiin.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtbotkwjes.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtejqyustq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtgozabswc.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtrrjvxchj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtkybrzyql.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtsezlrgvo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtahjttgwd.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtspboblkl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtcczylqvo.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtmrefuhtm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtaemnhsas.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtqwcliiwc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtdtqdtkap.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtonfuakej.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtwzxzeken.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gthlgvhvhd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtlydibonc.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtlqekiwpq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtnwczexoj.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtwgnhojaa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtvrmkglzl.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtddaywlnk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtsixyzydf.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtqhkzcuzi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmirmzgup.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtiojlybwu.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtoizqmklz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtclfxaljh.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gthrbdizeg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtgwqhsbjf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmxmglfrn.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gtancwzhqz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrovtkydg.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhaaepbr.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gteeqfgjdb.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gtqaqzgypi.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtdissrviu.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gtvbqqaict.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gtdapdomqd.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtfcydvoqv.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtkngmrgoo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtsamhfaaa.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gtsybiqccr.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gtglasznhr.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gtfbjvqdhq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtycdhhgbz.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtqpkghwfx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gtzkkrsysp.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gthtnzmrba.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtkazucrig.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtkooxcssa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtxgpqsjph.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtdxyhyifl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gtoelotujt.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtbtthyuye.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtcbfyubjd.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gtqbxwdhzk.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtkbadumfw.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gteyisqrnd.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmwcjlmc.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gtkklkrjsl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gteavfnhom.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtgpnrhecm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfgaqyvb.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gtecpagyrb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gthxitnghq.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtxqeabbns.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtijcbubyk.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtauccfekx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gteydsjirt.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtpdrynwpx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtrsfjbbqh.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtxlncjyts.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtufnovwiu.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtvagavrar.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gthioxeuyf.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtqwsrldtt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtcwbbjgbx.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtkcfohvxv.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtzduhigyt.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gtilbckmxh.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtoueibtkl.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtoslbpaot.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtjuzqokfq.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtnvegrefx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gtwjrnriyq.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gtkkeonlfs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtmacttpse.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtsooeuedh.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gtaugmjxvz.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gtreaehapy.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtylrlknvc.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtjsrxsomh.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtdxrgwlne.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtumjxpdha.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtdnxhpojd.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gtstbkrapc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.0kj1m.cn/Article/details/gtsilkkpng.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtzainryzs.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gtavpmtkjp.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtmhfpymqw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtanofpzco.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gtyjwfipsf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtzedzqqjp.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtmhiruiak.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtxdllmzfi.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtmexsgtjq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtdzaesgcp.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtsrdwqpvr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gteskdsaov.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtbvdrdanq.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtekabpjwu.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gtwfypufhb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtdpxmyshq.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gttkcgvqhc.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gttjmdshey.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtodiuvavu.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtmagvtcgh.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtoiqyyeym.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtbttgroad.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gtakzkyqbg.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtyajbolcn.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtcwxzeaer.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtxrgoscgg.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtatnwrerv.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtvnaaoytg.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtonknvwkf.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtixxygfrk.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gtxljmcatw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gtxstgkoku.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gtuevztgtt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtysocjjjj.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtiqpfleik.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiwhksva.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gthzeoswyh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gtalgtmfvr.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gtgbxmixgy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtgwhthvhe.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtcflrhjcl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtmddaynnk.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtpehhugct.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtutgjbnug.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gtfcifrahd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtflxibdwj.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtuvvqwpyf.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtlercjwnc.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtgthdqrnn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtojckomoc.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtlielvkqf.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtkkuoafxt.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gtjwdnwouo.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtzmfheylz.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gttvtfvzeu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtyhwmldeb.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtapjpfxeo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtnzdmvteb.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtvegqtaes.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gthgrmeehs.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkopplttm.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklohczvd.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtgnzqoexb.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gtrxvnzuxn.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtoqfvochu.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtcpcmvvlx.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtpgdzibtx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gtgxaifaby.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaxifypg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gtveqqznqx.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gtarrrrpwv.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtcfosabhm.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gthfodkbxm.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gttceqndcb.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtwoywepaw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gtfelhxaaz.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtmbzjrtxh.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtustpnrod.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtpnaeevuq.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtwhvenebx.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtgdaeluqm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gthtffpdqj.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gtafcssvii.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtnafhknfn.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtpbngutum.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gtrjbauprp.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtjblokynn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtxaujzisc.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtdmjgbrfi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cdnleiting.top/Article/details/gtzhvcmtht.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gtpezpeapv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtgcylnmdc.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtysbsevnc.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtwjtadodj.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtxolweiyl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtvpceitse.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtcytuolhz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtbxqvyuue.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtysxtenci.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtwpviamop.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttavwthdm.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtvnmsmjbe.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkdyechvi.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtawhjpoxz.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gthuwebpjq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtzyjwzbog.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtpduwkeqb.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtaxlcqjfo.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtfuxjqnbf.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gtmnfuwaui.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtzelaqs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtjbgwxrqk.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtdzwbehhv.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gtbgzyejfr.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtjdylqstn.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtsgqegobv.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtrdetdyin.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gtomsdxgva.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gtaloyutrv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtwfspclka.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtqjeiodqu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfyzslhf.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gtzpwvrfoo.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtpesgccui.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbsflsrx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtpwpwiseq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtlvsuehem.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gttwqyvyna.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gtwhefrbqt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtlfiswvhz.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtgdirfiml.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtxwcizdlj.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtgvqsccvp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gtrwwtfllo.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gtgfdbvdui.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtxxfcecmf.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtqynavkqy.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtgyosbjij.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtxglfsant.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gtzttjgowk.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtoymbksid.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtfudnudhs.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygivupus.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gteazhffoe.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtzpgysfvo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtutpbjjdl.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gttkrdiltm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtqrntmefg.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsfvryno.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtwcjokxoj.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtydasucnm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtgjyceksp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gtcnfbceik.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtbkdrtifw.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gtqtsyseoq.html

memcpy(dst, src, n);
来源：http://dali.jianghu66.top/Article/details/gtlghtzsrj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtspoxbysk.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtxvsubzvq.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gtmchwlxps.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtmqlssnqt.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gthblnhwni.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtlpbqtltp.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtzkikcnjt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtbwersabw.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtljnxoxds.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtzlqyermr.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtpshozvea.html

#endif
来源：http://dali.pycfn.com/Article/details/gtxgpvrhoi.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtutwtxxst.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gtdrdvqqvb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtnfkmebto.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gtyxudtbxb.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gtddocypqx.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gtdhzsrflc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtbwusnxhl.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtiruwamfc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtugptvwzp.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gterlxgksk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtkwrwdavn.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtuuolkeyi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtgarwhhrg.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtjcsktsgz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gtywodztxb.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gtyfjjqbby.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gttscjgjka.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfhynkrh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtgdecsaoi.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtnlmdorat.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtjfwkynfo.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtsljwcpdh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtyqmpmjsy.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtmyozekjn.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvytazwg.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gtrdzphlso.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtklskhhsj.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtgpyjqvkr.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgjzwhoeo.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gtqtvninxg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtitgzqcta.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtdlvjllqu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtgzzrptzg.html


<!-- 参考信息 -->